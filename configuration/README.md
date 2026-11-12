---
description: "Configure NFS Mobile from the back office."
---

# Mobile Configuration

## Overview

This section is for administrators. It describes the settings of the back office that change how NFS Mobile behaves for field users: which actions they can perform, how signatures and prices work, and how the search around a position behaves.

The topics are grouped in sub-sections:

| Sub-section | What it covers |
| ----------- | -------------- |
| [Application and Display Settings](application-and-display-settings.md) | The general settings, the distances unit, the search around a position, the remarks tab and the location logs. |
| [Intervention and Report Settings](intervention-and-report-settings.md) | The signatures, the photos, the reports, the abandoned interventions and the scan codes. |
| [Item and Price Settings](item-and-price-settings.md) | The products, the prices, the serial numbers and the extra fields of the items. |
| [Planning and Unavailability Settings](planning-and-unavailability-settings.md) | The hotel nights and the unavailabilities of the agenda. |

This section covers:

| Topic | Description |
| ----- | ----------- |
| [Application Settings for NFS Mobile](application-settings.md) | Find and read the **otmobile.settings** parameters. |
| [Signature Settings](signature-settings.md) | Set whether signatures are possible, mandatory and electronic. |
| [Search Around Settings](search-around-settings.md) | Set the limits of the search for sites and leads around a position. |
| [Price Calculation Setup](price-calculation-setup.md) | Set the products and prices used by the Items page of an intervention. |
| [Mandatory Serial Number Setup](mandatory-serial-number-setup.md) | Make the serial number of selected items mandatory. |
| [Scan Code Rules Setup](scan-code-rules-setup.md) | Limit the codes that the app accepts for a serial number. |
| [Serial Number Setup](serial-number-setup.md) | Choose where NFS stores the serial number scanned in the app. |
| [Required Photos Setup](required-photos-setup.md) | Require a minimum number of photos before an intervention is finished. |
| [Remarks Tab Setup](remarks-tab-setup.md) | Show or hide the Remarks shortcut. |
| [Abandoned Missions Setup](abandoned-missions-setup.md) | Choose how abandoned interventions are handled and restarted. |
| [Location Logs Setup](location-logs-setup.md) | Find the location logs and set the tracking. |
| [Measurement Unit Setup](measurement-unit-setup.md) | Choose kilometers or miles in the back office. |
| [Extra Item Fields Setup](extra-item-fields-setup.md) | Add extra fields to the items of an intervention. |
| [Mandatory Reports Setup](mandatory-reports-setup.md) | Make survey reports mandatory before an intervention is finished. |
| [Scan Task Setup](scan-task-setup.md) | Create scan tasks, including tasks whose code is recorded by the first scan. |
| [Intervention Scan Code Setup](intervention-scan-code-setup.md) | Give an appointment a code that users can scan. |
| [Swap Setup](swap-interventions-setup.md) | Allow users to swap two interventions. |
| [Automatic Suggestion Setup](automatic-suggestion-setup.md) | Turn on the suggestion of the next intervention near the technician. |
| [App Logs Setup](app-logs-setup.md) | Find the app logs that users send. |
| [Task Comment Setup](task-comment-setup.md) | Choose where the reason of a manual scan is saved. |
| [Button Labels Setup](button-labels-setup.md) | Rename the buttons of an intervention. |
| [Hotel Nights Setup](hotel-nights-setup.md) | Assign a hotel to a technician and show the rests. |
| [Agenda Handling Setup](agenda-handling-setup.md) | Choose which extra fields appear on the agenda. |
| [Unavailability Groups Setup](unavailability-groups-setup.md) | Group the unavailability types so that users pick a group first. |
| [Unavailability Days Setup](unavailability-days-setup.md) | Allow unavailabilities and set how many past days users can declare. |

## Before you begin

* You have access to the **Administration** module of NFS. See Customization > Application settings.
* You know which behavior you want to change. A setting changes the app for all its users, after they refresh their data.

{% hint style="warning" %}
Test a change on a test environment before you apply it to production.
{% endhint %}

<!-- REVIEW: the sprint review video shows these screens but does not name the profile or access right needed to open them. Confirm it, and replace the link of the first bullet with the right page of the back-office documentation. -->

## Related topics

* [Settings](../main-actions/settings.md)
* [Sign an Intervention](../intervention/sign-an-intervention/README.md)
* [Add Items to an Intervention](../intervention/add-items-to-an-intervention.md)
