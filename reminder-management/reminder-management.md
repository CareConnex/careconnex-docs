---
description: >-
  Automatically send appointment and event reminders to patients at the right
  time.
---

# Reminder Management

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* Set up treatment, consultation, and event reminders
* Configure reminder timing, channels, and message templates
* Activate, edit, or delete existing reminders
* Review reminder delivery history and status
* Troubleshoot reminder delivery issues
{% endhint %}

> 💡 **Reduce repetitive follow-ups with automated reminders**
>
> Once reminders are set up, Dr.OZ automatically sends appointment notices, follow-up messages, and event reminders based on the conditions you define.
>
> This helps your team spend less time sending routine messages manually while keeping patient communication timely and consistent.

***

## What Are Reminders?

Reminders automatically send important messages to patients based on their appointments or predefined event conditions.

📌 **Path: Inquiries > Reminders**

#### Common Ways to Use Reminders

* Send appointment information immediately after booking
* Remind patients one day before an appointment
* Send treatment-day instructions
* Send aftercare or follow-up information
* Notify patients about birthdays, ticket expiry, or other clinic events

#### ✅ Reminder Types at a Glance

<table><thead><tr><th width="130.11114501953125">Type</th><th width="176.00006103515625">Triggered by</th><th>Common Uses</th></tr></thead><tbody><tr><td><strong>Treatment</strong></td><td>Treatment appointment</td><td>Appointment reminders, pre- and post-treatment instructions</td></tr><tr><td><strong>Consultation</strong></td><td>Consultation appointment</td><td>Consultation reminders, schedule change notifications</td></tr><tr><td><strong>Event</strong></td><td>Event condition</td><td>Birthdays, ticket expiry, clinic added in the Dr.OZ app</td></tr></tbody></table>

> ⚠️ **Prepare your message templates before setting up reminders.**
>
> Reminders require registered message templates. If you have not created one yet, create it first in **Message Template Management**.
>
> For details on creating and approving templates, refer to the [**Message Template Management**](../consultation-management/message-template-management.md) guide.

***

## Add a Reminder

Go to **Inquiries > Reminders** and click **\[+ Add Reminder]**.

Reminders can be created as **Treatment**, **Consultation**, or **Event** reminders. Select the reminder type you want to use and follow the setup steps below.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

***

### Treatment Reminder

Treatment reminders are sent based on **treatment appointments registered in the schedule**.

They can be used for appointment reminders, pre-treatment instructions, aftercare guidance, and follow-up messages.

#### ① Enter a Reminder Name and Select Treatment

Enter a name for the reminder, then select **\[Treatment]** under Type.

#### ② Select the Service

Click **\[Select from List]**, then choose:

**Category → Treatment → Option**

Select the service that the reminder should apply to.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

> 💡 The service selected in the reminder must match the service assigned to the treatment appointment for the reminder to be sent correctly.

#### ③ Set the Trigger

Choose when the reminder should be sent.

* **Same Day:** Sends on the appointment date at the specified time.
* **Before:** Sends the specified number of days before the appointment date.
* **After:** Sends the specified number of days after the appointment date.

> 💡 **Instant**
>
> If **\[Instant]** is selected, the reminder is sent as soon as the appointment meets the configured conditions, without waiting for a separate delivery time.

#### ④ Choose a Delivery Method

Select how the reminder should be sent.

* **Send to All Selected Channels:** Sends the reminder through all selected channels.
* **Send in Selected Channel Order:** Sends the reminder through the selected channels in the configured order.

After selecting a delivery method, click **\[+ Add Channel and Template]**.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

#### ⑤ Select Channels and Templates

In the pop-up:\
• Select a **channel**, such as Dr.OZ App, WhatsApp, or KakaoTalk.\
• Select a **template** to preview the message on the right.\
• Review the message, then click **\[Select]**.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

> 💡 You can add multiple channels and templates to a single reminder.

#### ⑥ Save the Reminder

After completing the setup, click **\[Save]** in the upper-right corner.

You can view the saved reminder under **Inquiries > Reminders**.

Before using the reminder, check that:

* The reminder is active
* The correct service is selected
* The trigger and delivery time are correct
* The intended channels and templates are selected

***

### Consultation Reminder

Consultation reminders are sent based on **consultation appointments registered in the schedule**.

Unlike treatment reminders, you do not need to select a specific service.

<figure><img src="../.gitbook/assets/image (839).png" alt=""><figcaption></figcaption></figure>

> ⚠️ **Patient information must be linked to the consultation appointment for the reminder to be sent.**
>
> Even if a consultation appointment appears on the schedule, the reminder will not be sent if patient information is not linked to that appointment.

#### ① Select Consultation

Enter a reminder name and select **\[Consultation]** under Type.

#### ② Set the Trigger

Consultation reminders support the following trigger options:

* **Same Day**
* **Before**
* **After**
* **When Appointment Is Created**
* **When Appointment Time Changes**

> 💡 **Example**\
> Appointment created → Send consultation appointment information\
> 1 day before appointment → Send visit reminder\
> Appointment time changed → Send updated appointment information\
> After consultation → Send follow-up information

#### ③ Choose a Delivery Method

Choose how the reminder should be sent:

* **Send to All at Once:** Sends the reminder through all selected channels at the same time.
* **Send Sequentially:** Sends the reminder through the selected channels in order.

#### ④ Select Channels and Templates

Click **\[+ Add channel and template]**, then select the channel and template you want to use.

#### ⑤ Save

Once all settings are complete, click **\[Save]** in the upper-right corner.

The reminder will appear under **Inquiries > Reminders**.

***

### Event Reminder

Event reminders automatically send messages when a patient meets a **specific event condition**, rather than being triggered by an appointment.

<figure><img src="../.gitbook/assets/image (841).png" alt=""><figcaption></figcaption></figure>

> 💡 **How Event Reminders Are Different**
>
> Treatment and consultation reminders are based on appointments, while event reminders are triggered by **predefined patient or system events**.

#### ① Select Event and Choose an Event Condition

Select **\[Event]** under Type, then choose the event condition that should trigger the reminder.

Available event conditions include:

* **Birthday**
* **Ticket Expiry**
* **Clinic Added in the Dr.OZ App**

#### ② Set the Trigger

Choose when the reminder should be sent relative to the selected event:

* **Same Day**
* **Before**
* **After**

Then set the **send time** for the reminder.

> 💡 For example, you can send a birthday message on the patient's birthday or notify a patient before their ticket expires.

#### ③ Choose a Delivery Method

Choose how the reminder should be sent:

* **Send to All Selected Channels**: Sends the reminder through all selected channels at the same time.
* **Send in Selected Channel Order**: Sends the reminder through the selected channels in the configured order.

#### ④ Select Channels and Templates

Click **\[+ Add Channel and Template]**, then select the channels and message templates you want to use.

You can add multiple channels and templates to a single reminder.

#### ⑤ Save the Reminder

Once all settings are complete, click **\[Save]** in the upper-right corner.

The saved reminder will appear under **Inquiries > Reminders**.

***

## Manage Existing Reminders

You can review and manage registered reminders from **Inquiries > Reminder**.

Reminders are organized into **Treatment, Consultation, and Event** tabs. From the list, you can review the reminder name, trigger, delivery time, channels, and status.

### Activate or Deactivate a Reminder

Use the status toggle on the left side of the reminder to activate or deactivate it.

> 💡 If a reminder is not active, it will not be sent even when all other conditions are met.

### Edit or Delete a Reminder

Use the icons on the right side of the reminder to edit or delete it.

<figure><img src="../.gitbook/assets/image (842).png" alt=""><figcaption></figcaption></figure>

***

### Reminder Send Log

Use the **Reminder Send Log** to review reminder delivery results and troubleshoot failed messages.

📌 Path: **Inquiries > Reminder Send Log**

The log includes:

* Delivery date and time
* Reminder type
* Channel
* Recipient
* Delivery status

#### Review Delivery History

Use the **date range, phone number search, or filters** to find the reminder you want to review.

<figure><img src="../.gitbook/assets/image (843).png" alt=""><figcaption></figcaption></figure>

***

### Review Delivery History

Use the date range at the top of the page to view reminders sent during a specific period.

You can also search by phone number or use filters to narrow down the results.

<figure><img src="../.gitbook/assets/image (844).png" alt=""><figcaption></figcaption></figure>

***

### Check Why a Reminder Failed

If a reminder was not delivered, find the relevant record in the **Reminder Send Log**.

If the status is **Failed**, open **\[Message Delivery Failed]** to check the detailed failure reason.

<figure><img src="../.gitbook/assets/image (845).png" alt=""><figcaption></figcaption></figure>

> 💡 **Error Example: No Available Reminder Channel**
>
> If you see this error, check that the patient's **contact details and registration information for the selected channel** are entered correctly.

***

### Before Sending Reminders

Before using a reminder, check the following:

* The reminder is **active**.
* For treatment and consultation reminders, the appointment status is **\[Confirmed]**.
* Reminders are not sent for appointments in **\[Pending]** status.
* For **Treatment Reminders**, the service assigned to the appointment matches the service selected in the reminder.
* For **Consultation Reminders**, the required patient information is linked to the consultation appointment.
* If appointment information changes, confirm that the reminder still meets its delivery conditions.
* For external channels such as **WhatsApp** or **KakaoTalk**, confirm that the required template is approved.

> 💡 Creating a reminder does not send a message immediately. The message is sent automatically when the configured delivery conditions are met.

***

#### ⚠️ Things to Keep in Mind

* When reminders are sent through multiple channels, patients may receive the same information through more than one channel.
* Make sure the reminder is **active** after creating it.
* If appointment information changes, check that it still meets the reminder's delivery conditions.
* For external channels such as **WhatsApp or KakaoTalk** check the template approval status when necessary.

***

### ❓ Frequently Asked Questions

**Q. My reminder was not sent.**

Check the reminder status and delivery conditions first, then review the corresponding record in the **Reminder Send Log** for the delivery status and failure reason.

***

**Q. Can a reminder be sent more than once if the appointment time is changed repeatedly?**

Yes. If the **\[When Appointment Time Changes]** trigger is enabled, a message may be sent each time the consultation appointment time changes.

If repeated notifications are not required, review whether this trigger should remain enabled.

> External messaging channels such as WhatsApp may apply their own delivery policies to repeated automated messages. In some cases, repeated messages may be limited or filtered by the channel.

***

**Q. One patient did not receive the reminder. What should I check?**

If other patients received the reminder normally, first check that the patient's **contact information is correctly linked to the appointment**.

Then find the corresponding record in the **Reminder Send Log** and review its delivery status and failure reason.

***

**Q. How can I automatically send a treatment follow-up reminder three months later?**

For example, if you want to send a follow-up reminder three months after a treatment, set the treatment reminder trigger to:

* **Trigger:** \[After]
* **Days:** 90

Dr.OZ will then automatically send the reminder **90 days after the treatment appointment date**.
