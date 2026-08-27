---
description: >-
  Create and manage message templates for customer conversations and appointment
  reminders across different channels.
---

# Message Template Management

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* Create Inbox and reminder templates
* Configure and manage templates for each channel
* Use images, file attachments, and message variables
* Understand how template approval works for WhatsApp and Kakao AlimTalk
{% endhint %}

## Template Types

Go to **Inquiries > Templates** to create message templates for customer conversations and appointment reminders.

* **Inbox templates:** Reusable replies for frequently used messages during customer conversations
* **Reminder templates:** Messages sent through the **Dr.OZ app, WhatsApp, or Kakao AlimTalk** for appointment and visit reminders

> 💡 **Which template should I use?**\
> Use an **Inbox template** for messages you send repeatedly during customer conversations.\
> Use a **Reminder template** for messages that need to be sent according to an appointment schedule.

***

### Add a Template

All templates are created from the same starting point, regardless of the channel.

1. Go to **Inquiries > Templates** and click **+ Add Template**.
2. Select the channel you want to use and click **Confirm**.

Available channels:

* Inbox
* Dr.OZ
* WhatsApp
* KakaoTalk (AlimTalk)

<figure><img src="../.gitbook/assets/image (798).png" alt=""><figcaption></figcaption></figure>

> 💡 After you select a channel, you will be taken to the corresponding template creation screen. Available fields and features may vary by channel.

***

## Inbox Templates

Save frequently used replies as templates so your team can quickly insert them into customer conversations.

#### Common use cases

* Greeting or closing messages
* Clinic location and directions
* Business hours
* Out-of-office messages

After selecting **Inbox** from **Add Template**, enter the following information on the template creation screen.

1. Enter a **template name** and **message**.
2. Click **Save** in the upper-right corner.

<figure><img src="../.gitbook/assets/image (804).png" alt=""><figcaption></figcaption></figure>

> 💡 You can also add emojis, variables, images, and file attachments when creating a template.

***

### Use Message Variables

Variables automatically insert information related to the connected patient, clinic, or appointment into your message.

#### Add a Variable

1. Place your cursor where you want the variable to appear.
2. Click the **Variable** icon.
3. Select the variable you want to use and click **Insert**.
4. Save the message.

#### Available Variables

<table><thead><tr><th>Variable</th><th>Information</th><th width="88">Inbox</th><th width="85.77777099609375">Dr.OZ</th><th width="121.5555419921875">WhatsApp</th><th width="97.5555419921875">Kakao</th></tr></thead><tbody><tr><td><code>PatientName</code></td><td>Patient name</td><td>✓</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td><code>PatientPhone</code></td><td>Phone number</td><td>✓</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td><code>ClinicName</code></td><td>Clinic name</td><td>✓</td><td>✓</td><td>✓</td><td>✓</td></tr><tr><td><code>AgentName</code></td><td>Assigned agent</td><td>✓</td><td>✓</td><td>—</td><td>—</td></tr><tr><td><code>ReservationDate</code></td><td>Appointment date</td><td>—</td><td>✓</td><td>✓</td><td>✓</td></tr></tbody></table>

> 💡 A ✓ indicates that the variable is available for that channel.

***

### Use an Inbox Template

To use a saved template during a conversation, go to **Inquiries > Inbox** and click the **Template** icon(![](<../.gitbook/assets/image (326).png>)) in the message area.

> 💡 For detailed instructions on using templates in conversations, see the [**Messaging Features**](messaging-features.md) guide.

***

## Reminder Templates

Reminder templates can be used to send appointment-related messages through the **Dr.OZ app, WhatsApp, and Kakao AlimTalk**.

For external messaging channels such as **WhatsApp and Kakao AlimTalk**, only templates approved according to the channel's policies can be used.

***

### 1. Dr.OZ App

Use Dr.OZ app templates to send appointment and visit-related notifications through the Dr.OZ patient app.

After selecting **Dr.OZ** from **Add Template**, complete the template creation screen.

1. Enter the **template name** and **message**.
2. Add a variable or image if needed.
3. Click **Save**.

<figure><img src="../.gitbook/assets/image (805).png" alt=""><figcaption></figcaption></figure>

***

#### Use a Dr.OZ App Template

Dr.OZ app templates support patient name, phone number, clinic name, and **appointment date** variables.

You can use these variables to create messages such as appointment confirmations and reminders.

<figure><img src="../.gitbook/assets/image (806).png" alt="" width="563"><figcaption></figcaption></figure>

***

#### Edit a Template and Check Reminder Connections

Saved Dr.OZ app templates are available under the **Dr.OZ** tab.

Click the **Edit** icon next to a template to view or update:

* Template content
* Preview
* Connected reminders

The status shown in the template list indicates whether the template is currently available for use.

<figure><img src="../.gitbook/assets/image (807).png" alt=""><figcaption></figcaption></figure>

Under **Template Details > Connected Reminders**, you can see which reminders are using the selected template.

<figure><img src="../.gitbook/assets/image (808).png" alt=""><figcaption></figcaption></figure>

> 💡 For more information about connecting templates to reminders, see the [**Reminder Connection**](../reminder-management/reminder-management.md) guide.

***

### 2. WhatsApp

Use WhatsApp templates when you need to send a message after the customer's **24-hour messaging window has ended**, or when sending appointment reminders.

After selecting **WhatsApp** from **Add Template**:

1. Enter the **template name** and **message**.
2. Add variables, an image, or a **Dr.OZ App Download URL** button if needed.
3. Click **Save**, then click **Confirm** in the confirmation window to submit the template.

<figure><img src="../.gitbook/assets/image (809).png" alt=""><figcaption></figcaption></figure>

✅ **Add a ‘Dr.OZ App Download’ Button**

When creating a WhatsApp template, select the **Dr.OZ App Download** checkbox to include a link to the Dr.OZ app in the message.

This makes it easier for patients to access and install the app directly from the message.

***

### 3. KakaoTalk (AlimTalk)

Kakao AlimTalk templates must be configured according to Kakao's messaging requirements before they can be submitted for review.

After selecting **KakaoTalk (AlimTalk)** from **Add Template**:

#### 1. Choose a Category

Enter the template name, then select the **category and subcategory** that best match the purpose of the message.

***

#### 2. Choose a Message Type

Select either **Basic** or **Additional Information**, depending on how you want to structure the message.

* **Basic:** Best for standard informational messages
* **Additional Information:** Adds supplementary information below the main message

<figure><img src="../.gitbook/assets/image (811).png" alt=""><figcaption></figcaption></figure>

***

#### 3. Choose a Highlight Style

If you want to make important information stand out, choose **Image** or **Highlighted Text**.

* **Image:** Adds an image to the top of the message.
* **Highlighted Text:** Displays a title or key message more prominently.

<figure><img src="../.gitbook/assets/image (812).png" alt=""><figcaption></figcaption></figure>

***

#### 4. Add a Web Link Button

You can also add a **Web Link** button when needed.

Click **Add** in the button section, then enter:

* Button name
* Mobile web URL
* PC web URL

<figure><img src="../.gitbook/assets/image (815).png" alt=""><figcaption></figcaption></figure>

***

### Channel Template Comparison

Both **Kakao AlimTalk and WhatsApp** require templates to be registered and reviewed by the messaging provider before they can be used.

Only **approved templates** can be used for reminder messages. However, registration rules and review criteria differ by channel.

<table><thead><tr><th width="164.75">Category</th><th>WhatsApp</th><th>Kakao AlimTalk</th></tr></thead><tbody><tr><td>Review provider</td><td>Meta</td><td>Kakao</td></tr><tr><td>Message categories</td><td>Utility, Marketing, and Authentication messages</td><td>Informational messages that must be delivered to the customer</td></tr><tr><td>Main review focus</td><td>Whether the selected message category matches the actual content</td><td>Whether the content qualifies as an informational AlimTalk message</td></tr><tr><td>Advertising / Promotions</td><td>Promotional content can be submitted as a Marketing template</td><td>Promotional messages cannot be sent as AlimTalk</td></tr><tr><td>Appointment messages</td><td>Can be registered as Utility messages for confirmations, changes, and reminders</td><td>Should contain information directly related to the actual appointment</td></tr><tr><td>Common rejection reasons</td><td>Category mismatch, variable or formatting errors, policy violations, or inappropriate links and buttons</td><td>Promotional or benefit-focused wording, unclear notification purpose, unrelated images or buttons</td></tr></tbody></table>

***

### Template Approval

Once the review is complete, the template status in the template list changes to **Approved**.

<figure><img src="../.gitbook/assets/image (816).png" alt=""><figcaption></figcaption></figure>

> ⚠️ WhatsApp templates may be rejected or reassigned to a different category if the content does not match the selected category or does not comply with **WhatsApp Business messaging policies**.

***

### ❓ Frequently Asked Questions

#### I created an Inbox template, but it does not appear in the template list during a conversation.

Check whether the template is **active** in the template list.

Inactive templates are not displayed in the Inbox template menu.

***

#### My WhatsApp or Kakao AlimTalk template was not approved.

Templates may be rejected if the selected category does not match the actual message content.

For example, a message intended as an informational appointment or payment notification may be treated as promotional content if it includes discounts, events, or other marketing language.

Check the template status and rejection reason, update the content, and submit the template again.

* **WhatsApp:** [WhatsApp Business Messaging Policy](https://business.whatsapp.com/policy)
* **Kakao:** [Kakao AlimTalk Review Guide](https://kakaobusiness.gitbook.io/main/ad/infotalk/audit)

> 💡 For more information about using templates during conversations, see the [**Messaging Features**](messaging-features.md) guide.\
> For more information about linking patients to conversations, see the[ **Patient Linking**](patient-linking.md) guide.
