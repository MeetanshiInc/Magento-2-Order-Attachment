# **Magento 2 Order Attachment**

The **Magento 2 Order Attachment** extension allows store owners to attach files to orders, invoices, shipments, and credit memos. This feature helps businesses provide customers with essential documents such as invoices, shipping labels, and contracts.

 With this extension, the ordering process becomes more organized and efficient, improving customer satisfaction and overall store management.

## **How It Works**

The **Magento 2 Order Attachment** extension works by allowing the admin to attach various types of files to order-related documents, including invoices, shipments, and credit memos. These files can be uploaded directly from the admin panel and linked to specific orders, ensuring customers receive the necessary documents at each stage of their order process. The extension integrates seamlessly into the Magento workflow, making it easy to manage attachments without disrupting daily operations.

## **Key Features**

* Attach files to orders, invoices, shipments, and credit memos  
* Provide multiple file types, including PDFs, images, and documents  
* Configure access controls for file visibility (customer or admin only)  
* Enable automatic file attachments based on order status or conditions  
* Easily manage and view attachments from the Magento admin panel

## **File Attachment to Orders**

The Order Attachment extension for Magento 2 allows store owners to attach important files to orders, invoices, shipments, and credit memos. This feature helps provide essential information directly to customers, such as shipping labels, product manuals, or customized documents.

## **Role-Based File Access**

Magento 2 Order Attachment extension offers role-based permissions, allowing store administrators to define who can access, upload, and download attachments. This ensures that sensitive information is kept secure, and only authorized personnel can access certain files.

## **File Upload Customization**

The extension provides flexibility when it comes to file uploads. Store owners can customize the type of documents allowed and configure the maximum file size to ensure smooth performance and prevent server overload.

## **How to install Magento 2 Order Attachment Extension**

To install the Magento 2 Order Attachment extension:

### **Step 1:**

Extract the zip folder and upload our extension to the root of your Magento 2 directory via FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Order Attachment Extension**

To configure the extension, login to Magento 2, and move to **Stores \> Configuration** where you can find various settings to enable the extension.

### **Step 1: Navigate to Configuration**

![Navigate to Configuration](https://github.com/user-attachments/assets/c0ab58dd-b7e1-4b92-8e83-862e582626be)

* **Order Attachment:** Toggle the extension on or off from this setting.  
* **Attachment Directory:** Define the folder where uploaded attachments will be stored.  
* **Allowed File Extensions:** Specify the file extensions that are permitted for attachment uploads.  
* **Max. Attachment File Size:** Set the maximum allowed file size for uploaded attachments.

### **Step 2: Manage General Settings**

![Manage General Settings](https://github.com/user-attachments/assets/7dca6e99-a8f0-4f79-8d11-5e25625ed11e)

* **Enable Order Attachment for Customer Groups**: Choose the customer groups that are permitted to add order attachments.  
* **Allow Customers to Add Attachments to Existing Orders**: Set to **Yes** to allow customers to add attachments to their existing orders.  
* **Allow Customers to Delete Attachments**: Set to **Yes** to enable customers to delete attachments they’ve uploaded.  
* **Notify Customer When Admin Adds Attachment to Existing Orders**: Set to **Yes** to notify customers when an admin adds an attachment to an order from the backend.  
* **Notify Admin When Customer Adds Attachment to Existing Orders**: Set to **Yes** to notify admins when a customer uploads an attachment to an existing order.  
* **Allow Customers to Add Attachment from Checkout Page**: Set to **Yes** to enable customers to upload attachment files during the checkout process.  
* **Enable Comment Box on Checkout Page**: Set to **Yes** to activate a comment box on the checkout page, allowing customers to add comments for their orders.

### **Step 3: Customize Email Settings**

![Customize Email Settings](https://github.com/user-attachments/assets/4c74dcd7-aa6a-43a5-ba66-5317f13ddfce)

* **Enable**: Set to **Yes** to enable email notifications for both admins and customers.  
* **Admin Name**: Enter the admin's name that will appear in the notification emails.  
* **Admin Email**: Enter the admin's email address.  
* **Email Template**: Choose the template for the notification emails.  
* **Send Email to Customer About Attachment As**: Select the preferred option for sending order attachment emails to customers.  
* **Add Attachment in Email**: Set to **Yes** to include order attachments in the email notifications.

### **Step 4: Implement Order Attachment on the Frontend**

![Implement Order Attachment on the Frontend](https://github.com/user-attachments/assets/ae7d75b7-b7c9-4d18-9d72-5bb1d249ed2f)

After successfully configuring the extension, the Order Attachment feature will be available on the frontend. When customers add products to their cart and proceed to checkout, they will see an option to drag and drop files for uploading attachments, along with a comment box to add any additional notes.

* **Order Attachment Error Message**  
![Order Attachment Error Message](https://github.com/user-attachments/assets/9a7e029f-c24f-4cd2-8bce-9e6eda7bffec)

  If the uploaded attachment does not meet the extension's configuration criteria, an error message is displayed, as shown above.  
* **Order Attachment in an Order**  
![Order Attachment in an Order](https://github.com/user-attachments/assets/e7c3867e-9d09-439e-b2fe-a35d9df4a66c)
   
  Once an order is placed with an attachment, customers can view the uploaded files in the My Orders section under the order details. They also have the option to add comments and submit them directly from this page.

* ### **Order Attachment in the "My Order Attachments" Tab**

![Order Attachment in the My Order Attachments Tab](https://github.com/user-attachments/assets/050f0b7b-52f6-43e6-be51-6b6a10a25d28)

The extension allows customers to view all their order attachments in one place under the "My Order Attachments" tab within the "My Account" section.

### **Step 5: Order Attachment in the Backend**

![Order Attachment in the Backend](https://github.com/user-attachments/assets/7915fd15-adc2-408a-9a69-172f0e994f77)

In addition to the frontend, the extension also enables order attachments to be managed from the backend. Under Sales \> Orders, a dedicated Order Attachment tab is available. Here, admins can view attachments uploaded by customers and easily upload additional files by dragging and dropping them, submitting attachments on behalf of the customers.

### **Step 6: Order Attachment Emails**

* **Order Attachment Email to Admin**

![Order Attachment Email to Admin](https://github.com/user-attachments/assets/6c765ac3-6de0-438c-89a8-0b9ac7826044)

When a customer adds an order attachment, the admin receives an email containing the customer's details along with the attachment information.

* ### **Order Attachment Email to Customers**

![Order Attachment Email to Customers](https://github.com/user-attachments/assets/5eae42dc-911b-4bbd-9c6a-2c5239d53b67)

When the admin uploads order attachments from the backend, customers receive an email containing the order details and information about the attachments.

## Download our **[Magento 2 Order Attachment](https://meetanshi.com/magento-2-order-attachment.html)** Extension
