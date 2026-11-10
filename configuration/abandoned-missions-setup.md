---
description: "Choose how an abandoned intervention is handled in NFS, and whether the app can restart it."
---

# Abandoned Missions Setup

Choose how an abandoned intervention is handled in NFS, and whether the app can restart it.

## Overview

In NFS Mobile, the user taps **Abandon**. In the back office, the same intervention has another name: **Removed** (cancelled) or **Suspended** (on hold). A setting decides which one it receives, and only removed interventions are sent back to the app. The user can then restart them.

| Status in NFS | Behavior |
| ------------- | -------- |
| **Suspended** (on hold) | The appointment is on hold. It is not available in the planning and it is not sent to the app. |
| **Removed** (cancelled) | The appointment is cancelled. NFS sends it to the app, where it is displayed as **Abandoned**, and the user can restart it. |

## Choose the status of an abandoned intervention

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Open **OTMobile**, then **otmobile.settings**. See [Application Settings for NFS Mobile](application-settings.md).
3. Find the setting that starts with **cancelledStatus**. Its description is **When OTMobile mission is CANCELLED ('Abandon' button), OTGS status is SUSPENDED (instead of usual REMOVED status)**.
4. Turn it on to give the status **Suspended**, or off to give the status **Removed**.
5. Tap **Save** at the top right of the page.

To let the user restart abandoned interventions, the intervention must be **Removed**, so this setting must be off.

## Send abandoned interventions to the app

Cancelled interventions are displayed in the agenda of the app only when the sending of cancelled appointments is turned on in NFS. Turn it on, then ask your users to refresh their data.

## Find an abandoned appointment in NFS

1. Open the appointments or the agenda of the **Planning** module.
2. Filter the list on the abandoned appointments.
3. Check the appointment to restart.

<!-- REVIEW: the demo explains these rules in the questions at the end. Give the exact name of the setting that sends cancelled appointments to the app, the full name of the cancelledStatus setting, and the screen to filter abandoned appointments in NFS. -->

## Related topics

* [Restart an Abandoned Intervention](../intervention/restart-an-abandoned-intervention.md)
* [Abandon an Intervention](../intervention/abandon-an-intervention.md)
* [Application Settings for NFS Mobile](application-settings.md)
