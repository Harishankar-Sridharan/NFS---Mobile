---
description: "Limit the codes that the app accepts for the serial number of an item, with a regular expression."
---

# Scan Code Rules Setup

Limit the codes that the app accepts for the serial number of an item, with a regular expression.

## Overview

The **scanControlRegex** setting holds a regular expression, which is a pattern. When a technician scans the serial number of an item, the app accepts the code only if its content matches the pattern. A code that does not match is rejected with **Unknown item**. See [Accept Only Valid Scan Codes](../intervention/valid-scan-codes.md).

The pattern applies to the serial number of the items only. The scans of the task codes and of the intervention codes are not checked by it.

| Value | Behavior |
| ----- | -------- |
| Empty (default) | The app accepts every code. |
| A regular expression | The app accepts only the codes that match it. |

## Before you begin

* You know the format of the codes that your company uses, for example their length and their characters. A pattern that is too strict blocks valid codes.
* You have access to the **Administration** module.

## Set the pattern

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings**. See [Application Settings for NFS Mobile](application-settings.md).
3. Find **scanControlRegex**.
4. Enter the regular expression.
5. Click **Save**, then ask the users to log out and log in again.

### Example

This pattern accepts four formats:

* 19 digits, for example **1234567890123456789**.
* 13 digits, using `\d{13}`.
* The letter **E** followed by 15 letters or digits, or the letter **Q** followed by 8 letters or digits, for example **Q1A2B3C4X**.
* A semicolon followed by 19 digits.

```
^([0-9]{19}|\d{13}|[E][0-9A-Z]{15}|[Q][0-9A-Z]{8})|[;][0-9]{19}$
```

| Code | Result |
| ---- | ------ |
| 1234567890123456789 | Accepted |
| Q1A2B3C4X | Accepted |
| 123453456789 | Rejected: **Unknown item** |
| R12345678 | Rejected: **Unknown item** |

## Check the result in the app

1. In NFS Mobile, open an item of an intervention in progress.
2. Scan a code that follows the pattern. It is recorded.
3. Scan a code that does not follow it. The message **Unknown item** is displayed.

{% hint style="warning" %}
**Test your pattern**: Test it with real codes of your company before you apply it to production. The pattern is not checked for errors when you save it.
{% endhint %}

<!-- REVIEW: the team is looking at basic checks on the scanned content, such as a maximum length, and at the security of the scans. Confirm the exact name of the setting (scanControlRegex), the regular expression flavor that the app uses, and whether the pattern is also applied to typed numbers. -->

## Related topics

* [Accept Only Valid Scan Codes](../intervention/valid-scan-codes.md)
* [Application Settings for NFS Mobile](application-settings.md)
* [Serial Number Setup](serial-number-setup.md)
