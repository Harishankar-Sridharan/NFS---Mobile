# Cancel an Intervention

Cancel an intervention that you have started and return it to the accepted state.

## Overview

If you started an intervention by mistake, or you cannot carry on with it, you can cancel it. Cancelling an intervention does not delete it: its status returns from **In progress** to **Accepted**. You can then start the intervention again, or [abandon it](abandon-an-intervention.md).

## Before you begin

* The intervention is in progress. See [Start an Intervention](start-an-intervention.md).

## Cancel the intervention

1. Open the intervention. The status is **In progress** and a timer shows how long it has lasted.
2. On the **Intervention** page, tap **Cancel**.

<figure><img src="../.gitbook/assets/nfs-mobile-intervention-cancel-button.png" alt="Intervention in progress with the Finish and Cancel buttons" width="300"><figcaption><p>Intervention in progress with the Finish and Cancel buttons</p></figcaption></figure>

3. In the **Cancel the intervention** message, read the text **By confirming the cancellation, the status of the intervention will return to the accepted state.**
4. Tap **Confirm**. To close the message and keep the intervention in progress, tap **Cancel**.

<figure><img src="../.gitbook/assets/nfs-mobile-intervention-cancel-dialog.png" alt="Cancel the intervention message" width="300"><figcaption><p>Cancel the intervention message</p></figcaption></figure>

5. Wait while the message **Sending request in progress** is displayed.

<figure><img src="../.gitbook/assets/nfs-mobile-intervention-cancel-sending.png" alt="Sending request in progress" width="300"><figcaption><p>Sending request in progress</p></figcaption></figure>

## Check the result

The message **Status reverted to accepted successfully** is displayed. The **Intervention** page shows the status **Accepted**, and the **Begin** and **Abandon** buttons are displayed again.

<figure><img src="../.gitbook/assets/nfs-mobile-intervention-cancel-result.png" alt="Intervention returned to the accepted state" width="300"><figcaption><p>Intervention returned to the accepted state</p></figcaption></figure>

{% hint style="info" %}
The **Cancel** button on the **Intervention** page is displayed only while the intervention is in progress. For an accepted intervention that you cannot carry out, use **Abandon**. See [Abandon an Intervention](abandon-an-intervention.md).
{% endhint %}

<!-- REVIEW: confirm what happens to the timer, the report, the photos and the remarks already entered when an intervention is cancelled. The video shows the Reports shortcut still showing 2 after the cancellation, but does not show the report content. -->

## Related topics

* [Start an Intervention](start-an-intervention.md)
* [Finish an Intervention](finish-an-intervention.md)
* [Abandon an Intervention](abandon-an-intervention.md)
