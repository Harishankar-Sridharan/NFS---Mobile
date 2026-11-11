---
description: "Choose whether the reason of a manual scan replaces the comment of a task or is saved in a separate field."
---

# Task Comment Setup

## Overview

When a technician completes a scan task by hand, the app asks for a reason. A setting decides where the reason goes. See [Keep the Task Comment When You Scan by Hand](../intervention/task-comment-and-manual-scan.md).

| Setting | Comment of the task | Reason of the manual scan |
| ------- | ------------------- | ------------------------- |
| Not overwritten (on) | Kept in its filler, for example **filler 3** | Saved in a separate filler of the task |
| Overwritten (off) | Replaced by the reason | Written in the filler of the comment |

## Before you begin

* You have access to the **Administration** module. See [Application Settings for NFS Mobile](application-settings.md).
* You know in which fillers of the task your company stores the comment and the reason. See [Scan Task Setup](scan-task-setup.md).

## Keep the comment

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings**.
3. Find the setting that keeps the comment of the task when the user does not scan or scans by hand, and turn it on.
4. Click **Save**, then ask the users to log out and log in again.

## Check the result in NFS

1. In NFS, open an appointment and create a status task, for example **Task 01**, for the period **Before you start**. Enter a comment.
2. In NFS Mobile, begin the intervention and give a reason for the manual scan.
3. Refresh the appointment in NFS. In **Details of statusTasks**, check the fillers:
   * The comment is still in its filler.
   * The reason is in the separate filler.
4. Turn the setting off, log out and log in, and repeat the test. The reason now replaces the comment.

<!-- REVIEW: the demo does not show the screen of the setting. Give its exact name, and the numbers of the fillers (the audio says filler 3 for the comment and filler 5 or 6 for the reason). The team plans to add test cases for these scenarios. -->

## Related topics

* [Keep the Task Comment When You Scan by Hand](../intervention/task-comment-and-manual-scan.md)
* [Scan Task Setup](scan-task-setup.md)
* [Intervention and Report Settings](intervention-and-report-settings.md)
