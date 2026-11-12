---
description: "Choose which extra fields of an appointment appear on the interventions of the agenda."
---

# Agenda Handling Setup

## Overview

The appointment sheet of NFS Mobile shows the data items of the appointment, such as fillers, quantities, logical fields and dates, according to their **informationHandling** value. The **agendaHandling** value of a data item does the same for the agenda: when it is anything other than invisible, the item appears on the interventions of the agenda. See [See Extra Fields in the Agenda](../main-actions/extra-fields-in-the-agenda.md).

| agendaHandling | In the agenda |
| -------------- | ------------- |
| **unvisible** | The item is not displayed. |
| **writable** | The item is displayed. |
| **readonly** | The item is displayed. |
| **mandatory** | The item is displayed. |

## Before you begin

* You have access to the **Administration** module. See [Application Settings for NFS Mobile](application-settings.md).

## Show a field in the agenda

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings.dataItems**.
3. Find the data item that you want to show, for example the date filler.
4. Set **agendaHandling** to **writable**, **readonly** or **mandatory**. To hide the item again, set it to **unvisible**.
5. Repeat for each data item that you want to show, then click **Save**.
6. In NFS Mobile, refresh your data. See [Refresh Your Data](../main-actions/refresh-your-data.md).

{% hint style="info" %}
The values **unvisible**, **writable**, **readonly** and **mandatory** are the values that NFS already uses for the other handling settings. Their names are kept for compatibility with existing configurations.
{% endhint %}

<!-- REVIEW: the demo shows the screen of the data items only briefly. Confirm the exact path in the Administration module and the exact name of each data item. -->

## Related topics

* [See Extra Fields in the Agenda](../main-actions/extra-fields-in-the-agenda.md)
* [Planning and Unavailability Settings](planning-and-unavailability-settings.md)
* [Application Settings for NFS Mobile](application-settings.md)