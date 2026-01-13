# POS Categories

Configure product and service categories for POS integration.

## Overview

POS Categories define how transactions are categorized and how points are earned for different product types.

## Accessing POS Categories

Navigate to **POS Purchase > POS Categories**

<figure><img src="../../.gitbook/assets/unknown (23).png" alt=""><figcaption></figcaption></figure>

## Category List

| Column         | Description          |
| -------------- | -------------------- |
| Name           | Category name        |
| Division Code  | POS division mapping |
| Multiplier     | Point earning rate   |
| Sub Categories | Child categories     |
| Actions        | Edit/Delete          |

## Creating Categories

### Step 1: Click Add

Navigate to **POS Categories > Create Categories**

### Step 2: Enter Details

| Field              | Description            |
| ------------------ | ---------------------- |
| **Name**           | Category display name  |
| **Division Code**  | POS system code        |
| **Multiplier**     | Points multiplier      |
| **Sub Categories** | Child category details |

### Step 3: Add Sub Categories

Click **Add Sub Category** to create nested categories:

* Title
* Code
* Multiplier

### Step 4: Save

Click **Save** to create the category.

## Editing/Deleting Categories

* **Edit:** Action > Edit to modify
* **Delete:** Action > Delete to remove

## Importing Categories

### Import Division

1. Click **Import Division**
2. Download sample file
3. Fill in data
4. Upload file
5. Save

### Import Category

1. Click **Import Category**
2. Follow sample format
3. Upload and save

### Import Tender Type

1. Click **Import Tender Type**
2. Use sample template
3. Upload and save

## Update From FTP

Click **Update From FTP** to sync with external POS system.

## Best Practices

{% hint style="info" %}
* Use consistent naming conventions
* Map all POS divisions accurately
* Set appropriate multipliers
* Test point calculations
{% endhint %}

## Related Topics

* [POS Purchase Overview](./)
* [POS Tags](pos-tags.md)
* [Point Configuration](../main-settings/point-configuration.md)
