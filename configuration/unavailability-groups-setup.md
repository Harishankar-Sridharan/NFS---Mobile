---
description: "Group the unavailability types, so that users pick a group before the type."
---

# Unavailability Groups Setup

## Overview

Each unavailability type has a **Group name**. NFS Mobile reads the group names of all the types and builds the **Group concerned** list in the request form. When a user selects a group, the app lists only the types of that group. Types that have an empty group name are listed under **Unassigned**. See [Choose the Unavailability Type by Group](../menu/unavailabilities/choose-the-unavailability-type-by-group.md).

## Set the group of a type

1. In the **Administration** module, open **Unavailability type**.
2. Open a type, or click **Create an unavailability type**.
3. In **Group name**, enter the name of the group, for example **Absence**, **Personal** or **Internal Operation**. Use exactly the same spelling for the types of the same group.
4. Save.

The list of unavailability types shows the **Group name** of each type.

| Type | Group name |
| ---- | ---------- |
| Congés payés | Absence |
| Unscheduled Absence | Absence |
| Réunion, Formation | Internal Operation |
| Medical appointment, Family Emergency | Personal |
| Types with an empty group name | Appear under **Unassigned** in the app |

## Check the result in the app

1. In NFS Mobile, refresh your data. See [Refresh Your Data](../main-actions/refresh-your-data.md).
2. Open **Menu**, then **Unavailabilities**, then tap the plus button.
3. Open **Group concerned**. The groups that you defined are listed, and **Unassigned** is added when some types have no group.

{% hint style="info" %}
This feature is planned for the next version of the app. It needs the evolution of the back office that adds the group name.
{% endhint %}

<!-- REVIEW: confirm the name of the field in the back office (Group name), the version that has the evolution, and the effect of a type that requires validation. -->

## Related topics

* [Choose the Unavailability Type by Group](../menu/unavailabilities/choose-the-unavailability-type-by-group.md)
* [Unavailability Days Setup](unavailability-days-setup.md)
* [Application Settings for NFS Mobile](application-settings.md)
