---
description: Learn how to add, organize, edit, and manage your clinic's services in Dr.OZ.
---

# Service Management

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* View and manage your clinic's services
* Add a new service
* Organize services by category and display order
* Edit or delete a service
{% endhint %}

### Service Management Guide

> Use the **Services** menu to set up and manage the treatments and services offered by your clinic.
>
> Services created here are used when creating appointments, managing tickets and treatment sessions, and checking service pricing throughout Dr.OZ.

### 📌 Screen Overview

The Services page is divided into two main areas: the **service list on the left** and the **service details panel on the right**.

<figure><img src="../.gitbook/assets/image (702).png" alt=""><figcaption></figcaption></figure>

<table data-header-hidden><thead><tr><th width="89"></th><th width="211.66668701171875"></th><th></th></tr></thead><tbody><tr><td>No.</td><td>Feature</td><td>Description</td></tr><tr><td>①</td><td>Search</td><td>Search for a service by name</td></tr><tr><td>②</td><td>Status Filter</td><td>Filter services by <strong>All, Active, or Inactive</strong></td></tr><tr><td>③</td><td>Service Summary</td><td>View the total number of categories, services, active services, and inactive services</td></tr><tr><td>④</td><td>Category / Service List</td><td>Browse services organized by category, treatment, and treatment option</td></tr><tr><td>⑤</td><td>Service Details</td><td>View the selected service's duration, price, ticket settings, number of sessions, and validity period</td></tr><tr><td>⑥</td><td>Add Service</td><td>Add a new service</td></tr><tr><td>⑦</td><td>More Options</td><td>Manage categories and treatments or download the service list as a CSV file</td></tr><tr><td>⑧</td><td>Edit / Delete</td><td>Edit or delete the selected service</td></tr></tbody></table>

#### Service Structure

Services are organized in the following hierarchy:

**Category → Treatment → Treatment Option**

Example:

* **Injection** — Category
  * **Botox** — Treatment
    * **Forehead Botox** — Treatment Option

The **Treatment Option** is the actual service that staff select when creating an appointment or ticket.

***

### Add a Service

To create a new service, click **\[+ Add Service]** in the upper-right corner of the Services page.

Enter the service details in the **\[Add Service]** window.

<figure><img src="../.gitbook/assets/image (704).png" alt=""><figcaption></figcaption></figure>

### Step 1. Select a Category

Select the category the service belongs to.

* Once a category is selected, the treatments available under that category will become available.

***

### Step 2. Select a Treatment

Select the treatment the service belongs to.

* Treatments are used to group similar services within a category for easier management.

***

### Step 3. Enter the Treatment Option

Enter the name of the service that staff will actually select when creating an appointment or ticket.

For example:

* **Category:** Weight Management
* **Treatment:** Saxenda
* **Treatment Option:** 1 Pen

<div><figure><img src="../.gitbook/assets/image (705).png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/image (708).png" alt=""><figcaption></figcaption></figure></div>

> 💡 A **Treatment Option** is the actual bookable service used in day-to-day operations. We recommend using a name that your clinic staff can easily recognize when creating appointments.

***

### Step 4. Set the Duration

Enter the estimated duration of the service in **minutes**.

For example:

* 30 minutes
* 60 minutes
* 90 minutes

***

### Step 5. Enter Pricing Information

Enter the standard selling price for the service.

If the price may vary depending on the treatment area or other conditions, enter the standard price and use the **Memo** field to provide additional pricing information.

For example:

* Different prices by treatment area
* Other pricing rules or reference notes

> 💡 Use the **Memo** field for pricing details or other information that staff may need to check when using the service.

***

### Step 6. Configure Ticket Issuance

Set whether a ticket should be issued for the service, along with the number of sessions and validity period.

#### ① Ticket Status (ON/OFF)

* **ON:** A ticket is issued when the service is booked or paid for.
* **OFF:** Ticket issuance is disabled for this service.
* Turn this **ON** for packages or treatments that require session tracking.
* Leave this **OFF** for services that do not require ticket management.

#### ② Number of Sessions

Enter the total number of times the service can be used.

* For a single-session service, enter **1**.
* For a package, enter the total number of sessions included.

Example:

**5 sessions** means the ticket can be used five times.

#### ③ Ticket Validity Period

Select how long the ticket can be used after it is issued.

Example:

**365 days** means the ticket can be used for 365 days from the issue date.

If the ticket does not have an expiration period, select the option for **no expiration**.

> 💡 Turning ticket issuance **OFF** does not delete or deactivate the service itself.

***

### Step 7. Save the Service

After entering all service information, click **\[Save]** to complete the registration.

***

### Edit / Delete a Service

<figure><img src="../.gitbook/assets/image (709).png" alt=""><figcaption></figcaption></figure>

#### ① Edit a Service

* Select the service you want to update from the service list on the left.
* Click the **Edit (✏️) icon** in the upper-right corner.
* Update the information in the **\[Edit Service]** window, then click **\[Save]** to apply your changes.

#### ② Delete a Service

* To remove a service that is no longer needed, select the service and click the **Delete (🗑️) icon** in the upper-right corner.

> ⚠️ A service that has already been used for an appointment or ticket may be linked to existing records. Always check whether the service is currently in use before deleting it.

***

### Service Settings

Open the **More (⋯)** menu next to **\[+ Add Service]** to access additional service management options.

<figure><img src="../.gitbook/assets/image (710).png" alt=""><figcaption></figcaption></figure>

#### ① Category Settings

Add or edit the categories used to organize your services.

> Categories that already have services assigned to them may have restrictions on deletion.

#### ② Treatment Settings

Add or manage the treatments used to group your services.

Treatments created here become available for selection when adding a new service.

#### ③ CSV Download

Click **\[CSV Download]** to download the current service list as a CSV file.

The CSV file can be opened in Excel.

To save it as an Excel workbook (`.xlsx`), open the CSV file in Excel and select **Save As**, then change the file type to an Excel workbook.

> 💡 CSV export is especially useful when you have many services and want to review, organize, or back up the service list outside Dr.OZ.

***

### 💡 Tips

* Drag and drop **categories, treatments, and treatment options** to change their display order.
* Use the **+ / − controls** in the service list to expand or collapse categories and treatments.
* Use **Search** to quickly find a specific service when your clinic has a large service list.
* If a service has already been used for appointments or tickets, we recommend **deactivating it instead of deleting it** to avoid affecting existing records.
