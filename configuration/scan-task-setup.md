# Scan Task Setup

Create tasks that are completed by scanning a code, and tasks whose code is recorded by the first scan.

## Overview

The tasks of an appointment are stored as status tasks of the appointment. A task is a scan task when its code field is filled. In the demo, the code of a scan task is stored in a filler field that the custom settings map to the code of the task.

| Code of the task | Behavior in the app |
| ---------------- | ------------------- |
| A value, for example **123456** | The user must scan this code to complete the task. |
| A question mark (**?**) | The task has no code yet. The first scan completes the task and sends the scanned code to NFS. |
| Empty | The task is a normal task that the user taps, or reads with NFC. |

## Create a task with an unknown code

1. In NFS, open the appointment.
2. In **Details of statusTasks**, add the task and choose the stage: before accept, before start or during the intervention.
3. In the filler field that is mapped to the code, enter **?**.
4. Save the appointment.

## Check the result

1. In NFS Mobile, refresh your data, then open the intervention and tap **Tasks**.
2. Scan a code for the task. See [Scan a Task Code](../intervention/scan-a-task-code.md).
3. Finish the intervention, then refresh the appointment in NFS. The task shows the scanned code, the status **realized** and the date and time.

<!-- REVIEW: the demo does not show the screen to create the task. Give the exact name of the filler that is mapped to the code in the otmobile.settings.detailSets custom settings, and the page where the status tasks of an appointment are created. -->

## Related topics

* [Scan a Task Code](../intervention/scan-a-task-code.md)
* [Application Settings for NFS Mobile](application-settings.md)
