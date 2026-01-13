# Migration

Learn how to migrate customer data, points, and purchase history into the Loyalty CRM system.

## Overview

The Migration module allows administrators to import customer data from external sources or legacy systems.

## Accessing Migration

Navigate to **Customer > Migration List**

<figure><img src="../../.gitbook/assets/unknown (12).png" alt=""><figcaption></figcaption></figure>

## Migration Options

The system supports migration of:

| Data Type            | Description                       |
| -------------------- | --------------------------------- |
| **User Data**        | Customer profiles and information |
| **Points**           | Point balances and history        |
| **Purchase History** | Transaction records               |

## Viewing Migration Data

### Step 1: Access Migration List

Navigate to the Migration List section.

### Step 2: View Migration Records

The migration list displays:

* Migration ID
* Migration date
* Data type
* Status (Completed/Pending/Failed)
* Record count
* Action options

### Step 3: View Details

Click on a migration record to view:

* Individual record status
* Error logs
* Success/failure counts

## Migrating User/Points/Purchase History

### Step 1: Prepare Data File

Prepare your data file according to the required format:

* File format: CSV or Excel
* Download sample template for reference
* Ensure all required fields are populated

### Step 2: Access Migration Upload

Click **Migrate User/Points/Purchase History** or the corresponding import option.

### Step 3: Upload Data File

| Field           | Description                     |
| --------------- | ------------------------------- |
| **File Type**   | Select data type being imported |
| **Choose File** | Select file from your computer  |
| **Sample**      | Download sample format          |

### Step 4: Validate and Import

1. Click **Validate** to check data integrity
2. Review validation results
3. Fix any errors in the source file
4. Re-upload if necessary
5. Click **Import** to process the migration

## Data File Requirements

### User Data Format

| Column          | Required | Description        |
| --------------- | -------- | ------------------ |
| name            | Yes      | Customer full name |
| email           | Yes      | Email address      |
| mobile          | Yes      | Phone number       |
| nric            | No       | ID number          |
| dob             | No       | Date of birth      |
| gender          | No       | M/F                |
| address         | No       | Street address     |
| city            | No       | City               |
| postcode        | No       | Postal code        |
| old\_member\_id | No       | Legacy system ID   |

### Points Data Format

| Column      | Required | Description         |
| ----------- | -------- | ------------------- |
| member\_id  | Yes      | Customer identifier |
| points      | Yes      | Point balance       |
| type        | Yes      | Credit/Debit        |
| date        | Yes      | Transaction date    |
| description | No       | Transaction note    |

### Purchase History Format

| Column            | Required | Description         |
| ----------------- | -------- | ------------------- |
| member\_id        | Yes      | Customer identifier |
| transaction\_date | Yes      | Purchase date       |
| amount            | Yes      | Transaction value   |
| store             | No       | Store location      |
| items             | No       | Item details        |

## Migration Best Practices

{% hint style="info" %}
**Data Preparation:**

1. Clean data before migration
2. Remove duplicates
3. Standardize formats
4. Verify email/phone formats
5. Test with small sample first
{% endhint %}

{% hint style="info" %}
**Pre-Migration Checklist:**

* [ ] Back up existing data
* [ ] Validate source data quality
* [ ] Map fields to system requirements
* [ ] Prepare rollback plan
* [ ] Schedule during low-activity period
{% endhint %}

{% hint style="warning" %}
**Duplicate Handling:** The system will check for duplicates based on:

* Email address
* Mobile number
* NRIC/ID number

Decide handling strategy before import.
{% endhint %}

## Error Handling

### Common Migration Errors

| Error                  | Cause                  | Solution                |
| ---------------------- | ---------------------- | ----------------------- |
| Invalid email          | Malformed email format | Correct email format    |
| Duplicate record       | Member already exists  | Review duplicate policy |
| Missing required field | Empty mandatory column | Fill in required data   |
| Invalid date format    | Wrong date format      | Use YYYY-MM-DD format   |

### Reviewing Error Logs

1. Access migration record details
2. Download error log file
3. Review specific error messages
4. Correct source data
5. Re-attempt migration

## Post-Migration Verification

After successful migration:

1. **Verify counts** - Compare imported vs expected records
2. **Spot check** - Randomly verify individual records
3. **Test functionality** - Ensure members can login/transact
4. **Check reports** - Verify data appears in reports
5. **Document** - Record migration details for reference

## Related Topics

* [Customer Management](./)
* [Audience List](audience-list.md)
* [Reports](../reports/)
