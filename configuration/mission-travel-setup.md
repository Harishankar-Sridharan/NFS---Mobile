---
description: "Turn on the recording of the travel to an intervention, so that field users see the Start travel button."
---

# Mission Travel Setup

## Overview

A custom setting decides whether field users can record their travel to an intervention. When it is turned on, the **Start travel** button appears after the user accepts the intervention. See [Record a Mission Travel](../intervention/record-a-mission-travel.md).

| Setting | Result in NFS Mobile |
| ------- | -------------------- |
| **canRecordTrips** turned on | The **Start travel** button is displayed after the user accepts an intervention. |
| **canRecordTrips** turned off | The button is not displayed. The user begins the intervention directly. |

## Before you begin

* You have access to the **Administration** module. See [Application Settings for NFS Mobile](application-settings.md).

## Turn on the recording of the trips

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings**.
3. Find **canRecordTrips**: **Is it possible to record trips to missions?** Turn it on.
4. Click **Save**, then ask the users to log out and log in again.

## Check the result

1. In NFS Mobile, accept an intervention. The **Start travel** button is displayed.
2. Start, pause, resume and end a travel.
3. In NFS, open the appointment and refresh it. The sheet shows the progression status and the actual duration.

{% hint style="info" %}
For the accurate distance, the users must allow the location **all the time** and stop the optimization of the battery for the app.
{% endhint %}

<!-- REVIEW: the demo shows the setting canRecordTrips in the list of the application settings. Confirm its exact path, and the role of canPauseMissions, which is next to it, for the pause and the resume of a mission. -->

## Related topics

* [Record a Mission Travel](../intervention/record-a-mission-travel.md)
* [Intervention and Report Settings](intervention-and-report-settings.md)
* [Application Settings for NFS Mobile](application-settings.md)