---
description: "Rename the buttons of an intervention, in English, French and Italian, with the label keys of the mobile properties."
---

# Button Labels Setup

## Overview

Each stage of an intervention has buttons, such as **Accept**, **Refuse** or **Begin**. You can give them other labels for your company. NFS Mobile shows them in place of the default labels. See [Customized Appointment Button Labels](../intervention/customized-button-labels.md).

## The label keys

Each label has a resource key. Change only the value after the equal sign. Do not rename or delete the key.

| Resource key | Button |
| ------------ | ------ |
| `otmobile.customizable.label.intervention_accept_button` | Accept |
| `otmobile.customizable.label.intervention_refuse_button` | Refuse |
| `otmobile.customizable.label.intervention_begin_button` | Begin |
| `otmobile.customizable.label.intervention_abandon_button` | Abandon |
| `otmobile.customizable.label.intervention_finish_button` | Finish |
| `otmobile.customizable.label.intervention_start_undo_button` | Cancel, after the start |
| `otmobile.customizable.label.intervention_start_again_button` | Restart |
| `otmobile.customizable.label.intervention_plan_button` | Plan |

## Before you begin

* You can edit the properties files of the mobile application on the NFS server.
* You know the labels that you want, in each language.

## Change the labels

1. Open the file `otmobile.properties`. It holds the English labels.
2. Find the keys `otmobile.customizable.label...`.
3. Replace the value, for example `Confirm` for the accept button and `Complete` for the finish button.
4. For another language, edit the file of this language in the same way, for example `otmobile_fr.properties` for French and `otmobile_it.properties` for Italian, with the same keys.
5. Save the files.
6. Ask the users to log out and log in again.

{% hint style="info" %}
The app receives the labels in the language of the device when the user logs in. A user who changes the language of the device must log in again to get the labels of this language.
{% endhint %}

## Change a status label

The same method changes the label of a status, such as **Accepted**. Use the localization key of this status in place of the key of a button.

<!-- REVIEW: the demo shows the properties file but does not name the folder or the file path on the server, nor the key of the Accepted status. Give them, and the complete list of the labels that can be changed, which the team plans to extract from the source code. -->

## Related topics

* [Customized Appointment Button Labels](../intervention/customized-button-labels.md)
* [Intervention and Report Settings](intervention-and-report-settings.md)