---
description: "Set the limits of the search around a position."
---

# Search Around Settings

Set the limits of the search around a position.

## Overview

The app can search for entities around a position: events, customers and leads. These settings limit the number of results and the distance and travel time of the search. They also define the upper limits that a user can set in the app.

## Open the settings

1. Open **otmobile.settings**. See [Application Settings for NFS Mobile](application-settings.md#open-the-settings).
2. Find the parameters that start with **searchAround**.

## Parameters

| Parameter | Value in the video | Description |
| --------- | ------------------ | ----------- |
| **searchAroundMaxResults** | 20 | The maximum number of entities to find, for the searches around an event or a customer, and for the search for leads. |
| **searchAroundMaxResultsUpperLimit** | 1 | The upper limit of the maximum number of entities that a user can customize. |
| **searchAroundMaxTravelDistanceKilometers** | 100 | The maximum trip distance in kilometers. |
| **searchAroundMaxTravelDistanceKilometersUpperLimit** | 200 | The upper limit of the maximum trip distance that a user can customize. |
| **searchAroundMaxTravelTimeMinutes** | 80 | The maximum trip duration in minutes. |
| **searchAroundMaxTravelTimeMinutesUpperLimit** | 160 | The upper limit of the maximum trip duration that a user can customize. |

In the app, the user changes the three values in the **Configuration** section of the **Settings** page: **Maximum distance for research**, **Maximum travel time for research** and **Maximum number of results**. See [Settings](../main-actions/settings.md).

<!-- REVIEW: the value 1 for searchAroundMaxResultsUpperLimit is lower than the value 20 of searchAroundMaxResults in the video. Confirm that it is correct. -->

## Related topics

* [Application Settings for NFS Mobile](application-settings.md)
* [Browse the Sites List](../customer-directory/browse-the-sites-list.md)
