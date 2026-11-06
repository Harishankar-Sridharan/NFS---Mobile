# Location Logs Setup

Find the location logs sent by NFS Mobile and the settings that control the tracking.

## Overview

When a field user sends the location logs, or when the app sends them by itself, the file is stored in the back office. You can open it to check when the tracking started and stopped, and whether the positions were sent. See [Send Your Location Logs](../main-actions/send-location-logs.md).

## Find the log files

1. On the NFS server, open the multimedia folder of the NFS installation.
2. Open the folder of human resources, then the folder of the user. The folder is named with the external reference of the user, for example **HR_002**.
3. Open the **Logs** folder.
4. Open the file named **tracking_log** followed by the date and the time of the sending, for example **tracking_log_20250227141658.txt**.

<!-- REVIEW: confirm the exact path and file name. The demo shows an installation folder with webapps, a Multimedia folder, HumanResources and HR_002. -->

## Read a log file

The file lists, with the time of each event:

* The start and the stop of the background tracking, and the scheduled start and end times.
* The location permission and whether the app was in the foreground.
* Each position acquired, whether it equals the last known position, and whether the server update succeeded.
* The privacy mode, on or off.

Use it to check that positions are sent at the interval that you configured, and to see why a position is missing.

## Set the tracking interval

The interval between two positions is set in the back office, for example every one or two minutes. The tracking settings are found with the filter **tracking** in the **Application settings**. They include whether the tracking is enabled, whether the user can turn it off, the time of the day when it starts, and the timeouts.

<!-- REVIEW: the video shows the tracking settings only briefly. Name each setting and its default value, and confirm the tracking interval parameter. -->

## Check the tracking in NFS

1. In the **Tracking** module, open the tracking of the user.
2. Select the date. The map shows the tracking points with their time.

## Related topics

* [Send Your Location Logs](../main-actions/send-location-logs.md)
* [Application Settings for NFS Mobile](application-settings.md)
* [Privacy Mode](../menu/coworkers/privacy-mode.md)
