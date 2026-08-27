---
description: Manage invoices, payments, outstanding balances, and receipts in one place.
---

# Billing & Payments

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* Review billing status and invoice details
* Create an invoice
* Record full and partial payments
* View invoices and payment receipts
* Reconcile unreconciled package payments
* Cancel an invoice
{% endhint %}

## Billing Overview

Select **Billing** from the left menu to view your clinic's invoices and payment status.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

At the top of the page, you can quickly review the overall billing status.

* **Total Billed:** Total amount billed across all invoices
* **Total Collected:** Total amount received to date
* **Outstanding:** Amount that has not yet been paid
* **Partial Payments:** Number of invoices that have been partially paid

> 💡 Use the date and status filters, or search by **invoice number or patient name**, to quickly find the invoice you need.

### Invoice Status

* **Pending:** No payment has been recorded yet
* **Partially Paid:** Only part of the invoice amount has been paid
* **Paid:** The invoice has been paid in full
* **Cancelled:** The invoice has been cancelled

> 💡 If needed, select **Export** to save the invoice list as an Excel (CSV) file.

***

## Creating an Invoice

When a scheduled treatment is marked as **Completed**, Dr.OZ automatically creates an invoice based on the appointment details.

The invoice amount is calculated using the registered service and session information, so make sure the **service price and number of sessions** are set correctly.

You can also create an invoice manually from the Billing page when needed.

### Create an Invoice Manually

From the **Billing** page, click **\[+ Create Billing]** in the upper-right corner.

<figure><img src="../.gitbook/assets/image (846).png" alt=""><figcaption></figcaption></figure>

① Search for and select the **patient**.

② Review the **invoice date** and update it if needed.

③ Select the **invoice type**. You can also add a memo if needed.

④ Select the item to bill by choosing the **Type, Category, and Item**.

⑤ Review the **quantity, unit price, discount, and tax rate**, then click **\[Create]**.

> 💡 To include multiple items in the same invoice, click **\[+ Add Item]** before creating the invoice.

***

## Viewing Invoice Details

From the Billing list, select the **View Details** icon on the right side of the invoice you want to review.

<figure><img src="../.gitbook/assets/image (847).png" alt=""><figcaption></figcaption></figure>

| Invoice Information                                                           | Items                                                              | Summary                                                                   |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| Invoice number, invoice date, patient, status, invoice type, patient ID, memo | Item name, type, quantity, unit price, discount, tax, total amount | Subtotal, discount, tax, rounding, total, total paid, outstanding balance |

### Understanding the Summary

* **Subtotal:** Total of all invoice items before final adjustments
* **Total:** Final invoice amount
* **Total Paid:** Amount paid to date
* **Outstanding:** Remaining unpaid balance

***

### View the Invoice PDF

From the Invoice Details page, select **View Invoice** to open the invoice as a PDF.

You can review the invoice, download it, or print it as needed.

<figure><img src="../.gitbook/assets/image (848).png" alt=""><figcaption></figcaption></figure>

The invoice includes information such as:

* Clinic information
* Invoice number and invoice date
* Patient information
* Billed items
* Quantity and unit price
* Discounts and taxes
* Total billed amount
* Payment history and outstanding balance

> 💡 Use the **Download** or **Print** icon at the top of the PDF viewer to download or print the invoice.

***

## Recording a Payment

When you receive a payment from a patient, record it against an invoice with an outstanding balance.

From the Billing list, select the **Record Payment ($)** icon for the invoice.

Check the **outstanding balance** before entering the payment details.

<figure><img src="../.gitbook/assets/image (849).png" alt=""><figcaption></figcaption></figure>

① Select the payment date.\
② Select the payment method.\
③ Enter the payment amount.\
④ Enter a reference number if needed.\
⑤ Review the information and select **\[Record Payment]**.

* You can also enter a receipt number and memo if needed.

***

### Payment Methods

When recording a payment, select the appropriate payment method:

* Cash
* Credit Card
* Debit Card
* Online Transfer
* External Wallet
* Voucher
* Credit Wallet
* Other

> 💡 **Credit Wallet** can be used when the patient has an available wallet balance.

***

## Recording a Partial Payment

You can use the same **Record Payment** function to record a partial payment.

Enter an amount lower than the **outstanding balance**. The invoice will be marked as **Partially Paid**, and the remaining balance will remain **Outstanding**.

For example, if a patient pays **5,000** toward an outstanding balance of **35,000**, the remaining balance will be **30,000**.

When the patient makes another payment, select **Record Payment** again and enter the additional amount.

Once the invoice has been paid in full, the outstanding balance will become **0** and the invoice status will change to **Paid**.

<figure><img src="../.gitbook/assets/image (850).png" alt=""><figcaption></figcaption></figure>

> 💡 If a patient pays using multiple payment methods, record each payment separately using the appropriate payment method.

***

## Viewing Payment History and Receipts

Once a payment has been recorded, you can review it under **Payment History** at the bottom of the Invoice Details page.

The payment history shows information such as:

* Receipt number
* Payment date
* Payment method
* Payment amount
* Recipient
* Status

<figure><img src="../.gitbook/assets/image (851).png" alt=""><figcaption></figcaption></figure>

Select the **View Receipt** icon on the right side of a payment to open the receipt for that transaction.

\[Insert: Receipt PDF screenshot]

The receipt includes the patient's information, payment amount, payment method, and billed items.

A separate receipt is generated for each payment transaction. You can download or print the receipt PDF when needed.

> 💡 **Invoice vs. Receipt**
>
> * **Invoice:** Shows what the patient was billed for and the current payment status.
> * **Receipt:** Confirms that a specific payment was made and can be provided to the patient as proof of payment.

<figure><img src="../.gitbook/assets/image (852).png" alt=""><figcaption></figcaption></figure>

***

### Reconciling Unreconciled Packages

The **Unreconciled Packages** section shows package payments that have already been made but are not yet linked to the required invoice and payment record.

Use this section to create the missing billing records and complete the reconciliation.

<figure><img src="../.gitbook/assets/image (856).png" alt=""><figcaption></figcaption></figure>

① Select **\[Unreconciled Packages]**, then click **\[Record]** for the package you want to reconcile.

② In **Record Package Payment**, review the patient, package, session, price, and amount pending reconciliation. Confirm the payment details, then click **\[Record Payment]**.

Once recorded, the required invoice and payment record will be created and can be managed from the **Billing** page.

> ⚠️ **Before recording a package payment**\
> Check whether the same treatment or package payment has already been recorded on another invoice to avoid duplicate payment records.

***

### Cancelling Invoice

If a billing record was created incorrectly, you can cancel it from the **Billing Details** page.\
Click **\[Cancel Billing]**.

<figure><img src="../.gitbook/assets/image (861).png" alt=""><figcaption></figcaption></figure>

① Review the **billing number, patient, amount, and payment history** to make sure you are cancelling the correct billing record.

② Enter the **cancellation reason**.

③ Review the information, then click **\[Cancel Billing]**.

The billing record will be marked as **Cancelled** and excluded from billing statistics.

> ⚠️ **Check active payments before cancelling**
>
> If the billing has active payments, the linked payments will be **voided before the billing is cancelled**. Review the payment details carefully before proceeding.
>
> **This action cannot be undone.**

***

### 💡 Billing Workflow at a Glance

**Standard billing flow**

`Appointment Completed` → `Invoice Created` → `Review Invoice` → `Record Payment` → `View Receipt` → `Paid`

**For partial payments**

`Partially Paid` → `Check Outstanding Balance` → `Record Additional Payment` → `Paid`
