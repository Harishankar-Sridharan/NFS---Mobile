# Price Calculation Setup

Set the products and prices used by the Items page of an intervention.

## Overview

The **Items** page of an intervention lists products and calculates a total price. Each product is defined in the back office, with its unit price and its stock. The app multiplies the unit price by the quantity chosen by the user.

## Create or change a product

1. In the **Administration** module, open **Company data**, then **Product**.
2. Open a product, for example **Aigostar Adam 30GOM**.

<figure><img src="../.gitbook/assets/nfs-mobile-config-product-form.png" alt="Product form" width="600"><figcaption><p>Product form</p></figcaption></figure>

3. Fill in the fields of the product.

| Field | Description |
| ----- | ----------- |
| **Name** | The name displayed in the app. This field is mandatory. |
| **External reference** | The reference of the product in another system, for example **Adam**. |
| **Area** | The area where the product is available, for example **All areas**. This field is mandatory. |
| **Family** | The family of the product, for example **Boiler**. This field is mandatory. Product families are defined in **Product family**. |
| **Unit price** | The price of one unit, for example **50.0**. The app uses it to calculate the price. |
| **Stock** | The quantity in stock, for example **50.0**. |
| **Duration** | The duration of the product. |

4. Save the product.

## Check the result in the app

1. In NFS Mobile, open an intervention and tap **Items**. The product is listed with its unit price, for example **Boiler - UP ET : €50.00**.
2. Choose a quantity, then tap the calculator button. The **Result** page shows the price. See [Add Items to an Intervention](../intervention/add-items-to-an-intervention.md).

In the video, five Aigostar Adam 30GOM at **€50.00** give **€250.00**, and two Ariston HPC Plus at **€5.00** give **€10.00**. The page shows 7 items and a total price of **€260.00**.

<!-- REVIEW: confirm how the VAT is calculated (the app shows a dash), how the stock is updated when a quantity is used, and whether the unit price is excluding tax (UP ET). Add the other fields of the product form (Stock2, Load, Manpower, Priority) if they matter for the price. -->

## Related topics

* [Add Items to an Intervention](../intervention/add-items-to-an-intervention.md)
* [Mobile Configuration](README.md)
