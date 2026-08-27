---
description: >-
  Learn how to connect Plato Medical with Dr.OZ so your clinic can access
  patient information and medical records stored in Plato directly from Dr.OZ.
---

# Plato Medical Integration

{% hint style="info" %}
📘 **In this guide, you'll learn how to:**

* What information you need to connect Plato Medical
* How to configure the Plato Medical integration
* How to test and complete the connection
{% endhint %}

***

### Set Up the Plato Medical Integration

Once Plato Medical is connected to Dr.OZ, you can link Dr.OZ patients with their corresponding patient records in Plato and view their Plato medical records directly from the patient profile.

📌 **Go to: Settings > Clinic Settings > Plato Medical Integration**

<figure><img src="../.gitbook/assets/image (900).png" alt=""><figcaption></figcaption></figure>

#### ① Enter the Integration Details

Enter the information required to connect your clinic's Plato Medical account.

* **Database Name**: Enter the database name used by your clinic in Plato.
* **API Key:** Enter the Bearer API Key generated in Plato. You can generate an API Key from **System Setup > General Settings > API > Generate API Key** in Plato.
* **Default Calendar ID (Optional):** Enter the default Plato calendar ID, if applicable.
* **Default Location (Optional):** Enter the default clinic location, if applicable.
* **Default Doctor Code (Optional):** Enter the default doctor code, if applicable.

> 💡 Plato Medical settings may vary by clinic. Check your clinic's Plato configuration to ensure you enter the correct **Database Name, Calendar ID, Location, and Doctor Code.**

#### ② Test the Connection

After entering all required information, click **Test Connection**.

Dr.OZ will check whether it can successfully connect to Plato Medical using the information you entered.

#### ③ Save the Integration

Once the connection test is successful, click **Save** to complete the setup.

***

### After the Integration Is Set Up

Once Plato Medical is connected, go to **Patients > Patient Details > Plato Medical Records** to link a Dr.OZ patient to their corresponding Plato patient record and view their medical records.

For instructions on **finding and linking Plato patients, viewing medical records, refreshing Plato data, or unlinking a patient**, see the **Plato Medical Records** guide.
