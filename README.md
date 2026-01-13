# AzureStaticSiteLab(https://www.loom.com/share/84bddfc1a7ab4760a97299ab46f3b076)
# Azure Static Website Deployment Lab

## Objective
This lab demonstrates how to create an Azure Storage Account and deploy a simple static website using Azure Blob Storage.

---

## Step 1: Create a Storage Account
1. Log in to the **Microsoft Azure Portal**.
2. Click **Create a resource**.
3. Select **Storage accounts**.

---

## Step 2: Configure the Storage Account
1. Create or select a **Resource Group** for this project.
2. Enter a **unique, lowercase name** for the storage account (this will be used for future reference).
3. Select a **Region** closest to your location.
4. Leave all other settings at their **default values**.
5. Click **Review + Create**.
6. Select **Create** to deploy the storage account.

---

## Step 3: Enable Static Website Hosting
1. Once deployment is complete, navigate to the **Storage Account resource**.
2. Under **Data Management**, select **Static website**.
3. Toggle **Enable**.
4. Enter the name of your HTML file as the **Index document name** (e.g., `index.html`).
5. Save the configuration.

---

## Step 4: Upload Website Files
1. In the Storage Account menu, go to **Data Storage**.
2. Select **Containers**.
3. Click on the **`$web`** container.
4. Select **Upload**.
5. Upload your HTML file (the file can be created manually or generated using tools such as Claude.ai).
6. Confirm the upload.

---

## Step 5: Access the Static Website
1. Return to **Static website** under **Data Management**.
2. Copy the **Primary endpoint URL**.
3. Paste the URL into your web browser.

🎉 You have successfully deployed a simple static website using Azure Storage!

---

## Completion
This lab covered:
- Creating an Azure Storage Account
- Enabling static website hosting
- Uploading web content to Azure Blob Storage
- Accessing a live static website endpoint

✔️ Lab complete.
