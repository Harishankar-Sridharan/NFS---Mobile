---
description: "Choose where NFS stores the serial number scanned in NFS Mobile."
---

# Serial Number Setup

Choose where NFS stores the serial number scanned in NFS Mobile.

## Overview

When a field user scans or types a serial number for an item, NFS Mobile sends it to NFS with the intervention. The back office decides in which field of the appointment details the number is stored. By configuration, the serial number is mapped to a filler field of the product order detail. In the demo, it is stored in **Detail filler5**.

The number belongs to the item line of one appointment. It is not stored on the product. See [Scan or Enter a Serial Number](../intervention/scan-a-serial-number.md).

## Check the result in NFS

1. In NFS Mobile, scan or type a serial number for an item, then finish the intervention. See [Scan or Enter a Serial Number](../intervention/scan-a-serial-number.md#send-the-serial-numbers).
2. In NFS, refresh the appointment sheet.
3. In the details of the product order, look at the filler column to which the serial number is mapped, for example **Detail filler5**.
4. Check that each item shows its serial number. An item without a serial number has an empty cell.

## Show the product order details with the dedicated view

The product order details can be displayed with a dedicated layout, with a search and with dedicated fields such as the delivered quantity and the returned quantity. You can also add extra fields that are not planned.

1. In NFS, open the CRM settings, then the definition of the project details values.
2. Set the two parameters of the product order display to true.
3. Refresh the page.
4. Open the appointment. The product order details are displayed with the dedicated view and the search.

The dedicated view and the previous table view both work with NFS Mobile.

<!-- REVIEW: the demo shows these screens quickly. Give the exact names of the settings (page.crm.project.details.fields...), the property that maps the serial number to the filler (the presenter mentions product.order.mapping.append.user... and otmobile.settings, "Define otmobile's configuration"), the right access profile, and whether the filler used for the serial number can be changed. In the demo, the dedicated view did not show the serial number column until the filler was set to visible (filler5 and filler7 were mentioned); confirm the procedure. -->

{% hint style="warning" %}
Test the change on a test environment before you apply it to production. A parameter set in the wrong way can block the display of the appointment details.
{% endhint %}

## Related topics

* [Application Settings for NFS Mobile](application-settings.md)
* [Scan or Enter a Serial Number](../intervention/scan-a-serial-number.md)
* [Mobile Configuration](README.md)
