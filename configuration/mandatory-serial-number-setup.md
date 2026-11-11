---
description: "Make the serial number of selected items mandatory, with a logical field on the product or with the access type of the filler."
---

# Mandatory Serial Number Setup

Make the serial number of selected items mandatory, with a logical field on the product or with the access type of the filler.

## Overview

The serial number of an item can be mandatory in two ways. Both work for the items that your planner adds in NFS, and the second one also covers the items that the technician adds in the app.

| Way | Where you set it | Items concerned |
| --- | ---------------- | --------------- |
| **A logical field on the product line** | The project of the customer, in the product list | The products that come from the project, one by one |
| **The access type of the filler** | The detail set **productOrder** of the custom settings | Every item that uses this field, including the items added in the app |

A serial number that is mandatory shows a red asterisk (*) in the app, and blocks the end of the intervention until it is recorded. See [Scan the Mandatory Serial Numbers](../intervention/mandatory-serial-number.md).

## Before you begin

* The serial number is stored in a dedicated filler, mapped to the barcode of the item. See [Serial Number Setup](serial-number-setup.md).
* You have access to the **Administration** module and to the customer projects.

## Make the serial number of a product mandatory

1. In NFS, open the **customer** record, then the **project** tab.
2. In the product list of the project, find the product line, for example **Renault**.
3. Tick the logical field that is mapped to the mandatory scan, for example **logical3**. Leave it unticked for a product that does not need a serial number.
4. Save the project.

The project is copied to the appointments. The technician sees the asterisk on the product that is ticked, and no asterisk on the others.

## Map the logical field in the detail set

The logical field must be declared in the detail set so that the app knows that it means "mandatory scan".

1. In the **Administration** module, open **Customization**, then **Application settings**.
2. Under **OTMobile**, select **otmobile.settings.detailSets**, then the **productOrder** set. See [Extra Item Fields Setup](extra-item-fields-setup.md).
3. Find the name **mandatory scan** and check that it is mapped to the logical field that you use, for example **logical3**.
4. Click **Save**.

## Make the filler of the serial number mandatory

1. In the same **productOrder** set, find the filler that holds the serial number, for example **filler5**.
2. In **detailSetFieldAccess**, change its access from **writable** to **mandatory**.
3. Click **Save**.

Every item then needs a serial number, including the items that the technician adds from the catalogue.

## Check the result in the app

1. In NFS Mobile, log out and log in again. The app loads the new settings at login.
2. Open an intervention in progress, tap **Items**, then open an item.
3. Check the asterisk on **Serial number**.
4. Try to finish the intervention without a serial number. The message **Items – Please fill serial number for:** is displayed.

{% hint style="warning" %}
A change of the detail set applies to every user of the app. Test it first on a test environment.
{% endhint %}

<!-- REVIEW: the demo shows these settings quickly. Confirm the name of the field that holds the "mandatory scan" mapping, whether the logical field wins over the access type of the filler for a product of the project, and the needed version of NFS. -->

## Related topics

* [Scan the Mandatory Serial Numbers](../intervention/mandatory-serial-number.md)
* [Serial Number Setup](serial-number-setup.md)
* [Extra Item Fields Setup](extra-item-fields-setup.md)
