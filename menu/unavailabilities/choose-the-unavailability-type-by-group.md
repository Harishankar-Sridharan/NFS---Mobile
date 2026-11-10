# Choose the Unavailability Type by Group

Find the right type of unavailability faster, by picking its group first.

## Overview

When you declare an unavailability, the list of types can be long. The request form now asks for a **Group concerned** first. The list of types then shows only the types of that group. The groups come from the back office.

## Before you begin

* Your administrator has set the group of each unavailability type. See [Unavailability Groups Setup](../../configuration/unavailability-groups-setup.md).
* You know how to open your unavailabilities. See [Unavailabilities](README.md).

## Declare an unavailability with a group

1. In the navigation bar, tap the **Menu** icon, then tap **Unavailabilities**.

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-menu.png" alt="Menu" width="300"><figcaption><p>Menu</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-list-empty.png" alt="Unavailabilities list" width="300"><figcaption><p>Unavailabilities page</p></figcaption></figure>

2. Tap the plus button at the bottom right. The **New request** page opens.

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-new-request.png" alt="New request" width="300"><figcaption><p>New request</p></figcaption></figure>

3. Tap **Group concerned**. The list shows the groups, for example **Absence**, **Personal**, **Internal Operation** and **Unassigned**.

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-groups.png" alt="Groups" width="300"><figcaption><p>List of groups</p></figcaption></figure>

4. Select a group. A **Type of unavailability** field appears under it.
5. Tap **Type of unavailability**. The list shows only the types of the group that you selected.

| Group | Types in the example |
| ----- | -------------------- |
| **Absence** | Congés payés, Unscheduled Absence |
| **Internal Operation** | Formation, Réunion |
| **Personal** | Family Emergency, Medical appointment |
| **Unassigned** | The types that have no group, for example No Default location but Location required, Passage au dépôt and RTT |

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-absence-types.png" alt="Types of the Absence group" width="300"><figcaption><p>Types of the Absence group</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-internal-types.png" alt="Types of the Internal Operation group" width="300"><figcaption><p>Types of the Internal Operation group</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-personal-types.png" alt="Types of the Personal group" width="300"><figcaption><p>Types of the Personal group</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-unassigned-types.png" alt="Types without a group" width="300"><figcaption><p>Types of the Unassigned group</p></figcaption></figure>

6. Select the type, for example **Congés payés**.
7. Fill in the date, the times and the comment, as described in [Declare an Unavailability](declare-an-unavailability.md).

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-filled.png" alt="Request filled in" width="300"><figcaption><p>Request filled in</p></figcaption></figure>

8. Tap **Declare**. Wait for **Sending request in progress**, then **Successfully sent**.

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-sending.png" alt="Sending request in progress" width="300"><figcaption><p>Sending request in progress</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/nfs-mobile-unavcat-sent.png" alt="Successfully sent" width="300"><figcaption><p>Successfully sent</p></figcaption></figure>

To change the group, tap **Group concerned** again and select another one. The list of types changes with it, and you must select a type again.

{% hint style="info" %}
The button is **Declare** for a type that needs no validation. For a type that your planner must validate, the button is **Send request**, and the unavailability is created with the status **Requested**.
{% endhint %}

<!-- REVIEW: this feature is planned for the next version of the app. Confirm the version, and confirm the label of the button for a type that needs validation. -->

## Related topics

* [Declare an Unavailability](declare-an-unavailability.md)
* [Unavailabilities](README.md)
* [Unavailability Groups Setup](../../configuration/unavailability-groups-setup.md)
