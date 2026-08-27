---
description: >-
  Use AI to quickly understand patient conversations, review suggested
  responses, manage bookings, and automate responses.
---

# Dr.OZ AI Assistant

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* Review AI-generated conversation insights and suggested responses
* Create and manage bookings directly from a conversation
* Understand AI response modes and auto-reply status
{% endhint %}

> 💡 For conversations in other languages, see the [AI Multilingual Consultation guide](ai-multilingual-consultation.md) to learn how to respond in the patient's preferred language.

***

### Dr.OZ AI Panel

The **Dr.OZ AI panel** analyzes the conversation and provides helpful information such as a **conversation summary, patient intent and sentiment, suggested responses, required actions, and Quick Booking options**.

You can also create, update, or delete an appointment directly from the conversation without opening the Schedule page.

📌 **Path:** Inquiries → Inbox → Select a conversation → **\[Dr.OZ AI]** panel

> 💡 **Using Dr.OZ AI for the first time?**\
> Dr.OZ AI requires an AI model and knowledge base to be configured before use. Auto-reply features are only displayed for branches where the feature has been enabled.\
> See the [**AI Assistant Settings**](../settings/ai-assistant-settings.md) guide for setup instructions.

***

### Dr.OZ AI Panel Overview

The Dr.OZ AI panel provides the following information and features:

* Conversation summary
* Patient intent
* Sentiment
* Suggested responses
* Required actions
* Quick Booking

<figure><img src="../.gitbook/assets/image (820).png" alt=""><figcaption></figcaption></figure>

**① \[Dr.OZ AI] tab** → Open the full AI panel to view the conversation summary, patient intent, suggested responses, required actions, Quick Booking, and more.

**② \[AI Suggestions] icon** → Quickly view AI-generated response suggestions.

> 💡 AI-generated insights are provided to assist your team. Always verify important details against the actual conversation before taking action.

***

### Review and Send Suggested Responses

The **Dr.OZ AI** panel uses the current conversation and information registered by your clinic to suggest responses you can send to the patient.

① Under **Suggested Responses**, select the response that best matches the conversation.

② Review the message in the message input field, then click **Send** or press **Enter**.

<figure><img src="../.gitbook/assets/image (822).png" alt=""><figcaption></figcaption></figure>

> ⚠️ AI-generated responses are provided for reference. Before sending, always check important details such as the **patient's name, date, and time**.
>
> You can edit the suggested response before sending to better match the patient's inquiry.

***

### Manage Bookings During a Conversation

With **Quick Booking**, you can create appointments directly from the conversation.

① In **Quick Booking**, select the **calendar icon**.

② Select the **appointment date**.

③ Select the **doctor or staff member** who will handle the appointment.

④ Select an **available time**, review the booking details, and click **\[Confirm Booking]**. Add a note if needed.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

#### Send Booking Details to the Patient

After creating the booking, you can send the appointment details directly to the patient.

① Review the created booking and click the **send icon**.

② The appointment details will be added to the message input field. Review the message, then send it to the patient.

<figure><img src="../.gitbook/assets/image (823).png" alt=""><figcaption></figcaption></figure>

***

### Edit or Delete a Booking

Bookings created through Quick Booking can also be updated or deleted from the same panel.

* **Edit (✏️):** Change the appointment date, time, or assigned staff member.
* **Delete (❌):** Review the appointment and confirm deletion.

> ⚠️ Before editing or deleting an appointment, confirm the **patient, appointment date, and assigned staff member**. After making changes or cancelling the booking, make sure the patient is informed of the final appointment status.

***

## Using AI Auto-Reply

Dr.OZ AI analyzes patient inquiries and generates responses using information registered in your clinic's **knowledge base**.

Dr.OZ AI supports two response modes:

#### 🟢 Approve Before Sending

AI prepares a draft response for inquiries it can answer.

A staff member reviews the response, edits it if necessary, and approves it before it is sent to the patient.

> AI: “I can answer this inquiry. I've prepared a draft for you to review before sending.”

#### 🟠 Auto-Reply

For general inquiries that AI can confidently answer, the response is sent directly to the patient without staff approval.

If AI determines that an inquiry should not be handled automatically, staff review is required.

> AI: “This inquiry should be reviewed by a staff member before a response is sent.”



> 💡 Auto-Reply availability, response mode, allowed topics, and staff handoff conditions can be managed under Settings > Clinic Settings > AI Assistant Settings.

***

### Response Mode Comparison

Auto-Reply availability and response behavior can be configured by branch. How an inquiry is handled may also vary depending on the content of the patient's message.

| Scenario                                                             | AI Action                                                          | Staff Action                        |
| -------------------------------------------------------------------- | ------------------------------------------------------------------ | ----------------------------------- |
| General inquiry + **Approve Before Sending**                         | AI prepares a draft response                                       | Review, edit if needed, and send    |
| General inquiry + **Auto-Reply**                                     | AI responds directly to the patient                                | Review the conversation when needed |
| Medical, booking, complaint, or other inquiry requiring staff review | AI does not respond directly and flags the conversation for review | Respond to the patient directly     |

> 💡 Auto-Reply availability, response mode, allowed topics, and staff handoff conditions can be managed under Settings > Clinic Settings > AI Assistant Settings.

***

## AI Response Status

The conversation list uses status indicators to help you quickly identify how an AI-generated response is being handled.

#### 🟢 Green — AI Draft Available

AI has generated a response based on your clinic's knowledge base.

Review the response and edit it if necessary before sending.

#### 🟠 Orange — Staff Review Required

AI has determined that the inquiry should not be answered automatically.

A staff member should review the conversation and respond directly.

> 📌 Conversations requiring prompt staff attention may display a **Priority Review** indicator in the conversation list.

***

## When Using Approve Before Sending

After AI generates a response, you can send it as written or edit it before sending.

* **Edit:** Modify the AI-generated response.
* **Approve & Send:** Review the response and send it to the patient.
* **Dismiss:** Close the AI draft without using it.

> 💡 You do not need to send an AI-generated response exactly as written. Edit the response as needed to match the patient's situation and your clinic's communication guidelines.

***

## When Using Auto-Reply

With Auto-Reply enabled, AI can respond to general inquiries without staff approval.

Examples include:

* Clinic operating hours
* Clinic location and parking information
* Service information
* Other general information available in the clinic's knowledge base

✅ Responses sent automatically by AI can be reviewed in the conversation history.

***

## When Staff Review Is Required

Some inquiries should not be handled directly by AI and may require review by your team.

Examples include:

* Questions involving symptoms, pain, or medical judgment
* Appointment or schedule change requests
* Complaints or negative feedback
* Requests to speak with a staff member
* Questions where the answer cannot be reliably verified from the knowledge base
* Conversations that have reached the Auto-Reply limit

When staff review is required, a notice appears in the conversation. Conversations that require prompt attention may also display a **Priority Review** indicator in the conversation list.

***

## Important Notes When Using AI Responses

* AI responses are generated using information registered in your clinic's **knowledge base**.
* When using **Approve Before Sending**, always review the response and edit it if necessary before sending.
* If a response includes important information such as a **patient name, appointment schedule, or price**, verify it against the actual information before sending.
* Even when Auto-Reply is enabled, we recommend reviewing conversation history regularly.
* If an AI response is inaccurate or outdated, check and update the relevant information in the **knowledge base**.

> ⚠️ AI responses are designed to assist your team. **Do not rely solely on AI responses for inquiries that require medical judgment.**
