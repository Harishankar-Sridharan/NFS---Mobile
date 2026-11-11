---
description: "Give an appointment a code that users can scan to open it in NFS Mobile."
---

# Intervention Scan Code Setup

## Overview

In the demo, the code of an appointment is stored in an extra field of the appointment, for example **Extra filler 1**, with the value **scan_APPT_1738**. When a user scans a barcode or a QR code with this value, the app opens the appointment. See [Open an Intervention with a Scan](../main-actions/open-an-intervention-with-a-scan.md).

## Set the code of an appointment

1. In NFS, open the appointment.
2. In **Extra fields**, enter the code in the field that is used for it, for example **Extra filler 1**. Enter **scan_APPT_1738** in the demo.
3. Save the appointment.

## Create the barcode

1. Use a barcode or QR code generator.
2. Enter the same value as the code of the appointment.
3. Choose **QR code**, or another type that the app can read, and print or display it.

## Check the result in the app

1. Refresh your data in NFS Mobile.
2. In the calendar options, tap **Access an intervention** and scan the code.
3. The appointment opens.

<!-- REVIEW: the demo shows the code in the extra field of the appointment and the generated QR code, but not the setting that maps this field. Give the name of the field or the setting that the app uses, and the list of barcode types that it reads. -->

## Related topics

* [Open an Intervention with a Scan](../main-actions/open-an-intervention-with-a-scan.md)
* [Application Settings for NFS Mobile](application-settings.md)
