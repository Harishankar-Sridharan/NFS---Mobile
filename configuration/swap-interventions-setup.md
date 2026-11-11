---
description: "Allow field users to swap two interventions of their agenda."
---

# Swap Setup

Allow field users to swap two interventions of their agenda.

## Overview

The **canSwapMissions** setting of **otmobile.settings** turns the swap on or off. Its description is **Is it possible to swap two missions planned for the same technician?**

| Value | Effect |
| ----- | ------ |
| **true** | The quick actions of an intervention offer **Select for swap**. |
| **false** | The swap is not offered. |

The back office decides whether a swap is possible. It answers possible, possible with a force, or impossible. See [Swap Two Interventions](../main-actions/swap-interventions.md).

## Before you begin

* You have access to the **Administration** module. See [Application Settings for NFS Mobile](application-settings.md).
* You know that the swap applies to every user of the app.

## Turn the swap on

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings**.
3. Find **canSwapMissions** and turn the switch on.
4. Click **Save**, then ask the users to log out and log in again.

## Check the result in the app

1. In NFS Mobile, open the **Calendar**.
2. Press a **Confirmed** or **Accepted** intervention for a long time.
3. Check that **Select for swap** is in the quick actions.

{% hint style="info" %}
Only the interventions that are **Confirmed** or **Accepted** can be swapped.
{% endhint %}

<!-- REVIEW: the demo shows only this setting. Confirm whether other settings of the back office change when a swap needs a force, and which reasons the back office can return. -->

## Related topics

* [Swap Two Interventions](../main-actions/swap-interventions.md)
* [Application Settings for NFS Mobile](application-settings.md)
* [Planning and Unavailability Settings](planning-and-unavailability-settings.md)
