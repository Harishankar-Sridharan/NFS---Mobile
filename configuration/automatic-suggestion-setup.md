---
description: "Turn on the geofencing that lets the app suggest the next intervention near the technician."
---

# Automatic Suggestion Setup

## Overview

A setting of **otmobile.settings** about the geofencing decides whether the app suggests the interventions by itself. When it is **true**, the app suggests an intervention when the technician is within 500 meters of its address and its time is within 30 minutes. See [Get Suggested Interventions Near You](../main-actions/suggested-interventions.md).

| Value | Effect |
| ----- | ------ |
| **true** | The app suggests the interventions. |
| **false** | The app does not suggest anything. |

The setting is not dedicated to this feature. The presenter says that it already existed, and that its description is **Can use geofencing for user**.

## Before you begin

* You have access to the **Administration** module. See [Application Settings for NFS Mobile](application-settings.md).
* Your users know that the app uses their position. The privacy mode of a user stops the suggestions. See [Privacy Mode](../menu/coworkers/privacy-mode.md).

## Turn the suggestion on

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings**.
3. In the filter, enter **geofenc** to find the setting.
4. Turn the switch on.
5. Click **Save**, then ask the users to log out and log in again.

## What the user needs

* The intervention is **Accepted**, or the technician has begun it, and not started yet.
* The privacy mode is off, and the location and notifications are allowed for the app.

<!-- REVIEW: the demo does not show the screen of the setting. Give its exact name in otmobile.settings. The rules (500 meters, 30 minutes, 10 minutes of ignore, check every two minutes) come from the presenter. Confirm whether they can be changed. -->

## Related topics

* [Get Suggested Interventions Near You](../main-actions/suggested-interventions.md)
* [Application Settings for NFS Mobile](application-settings.md)
* [Planning and Unavailability Settings](planning-and-unavailability-settings.md)
