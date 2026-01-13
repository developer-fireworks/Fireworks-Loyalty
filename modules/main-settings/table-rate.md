# Table Rate

Learn how to configure spending-based point earning tables in the Loyalty CRM system.

## Overview

Table Rate configurations allow you to create tiered or progressive earning structures based on spending amounts.

## Accessing Table Rate

Navigate to **Main Settings > Table Rate**

## What is Table Rate?

Table rates define how points are earned based on:
- Spending thresholds
- Category classifications
- Transaction types
- Promotional periods

## Table Rate Types

### Flat Rate

Same earning rate regardless of spend:
```
All Transactions: 1 point per RM 1
```

### Tiered Rate

Different rates based on transaction value:
```
RM 0 - 50: 1 point per RM
RM 51 - 100: 1.5 points per RM
RM 101+: 2 points per RM
```

### Category-Based Rate

Different rates by product/service category:
```
Fashion: 1 point per RM
F&B: 2 points per RM
Electronics: 0.5 points per RM
```

## Configuring Table Rates

### Step 1: Access Table Rate Settings

Navigate to the Table Rate configuration page.

### Step 2: Create New Table

| Field | Description |
|-------|-------------|
| **Table Name** | Descriptive name |
| **Description** | Purpose of the table |
| **Status** | Active/Inactive |
| **Priority** | Order of application |

### Step 3: Define Rate Tiers

| Field | Description |
|-------|-------------|
| **Minimum Amount** | Lower threshold |
| **Maximum Amount** | Upper threshold |
| **Points Rate** | Points per unit |
| **Multiplier** | Additional multiplier |

### Step 4: Set Application Rules

Define when the table applies:
- All transactions
- Specific categories
- Specific tenants
- Date range
- Member tiers

### Step 5: Save Configuration

Click **Save** to activate the table.

## Example Configurations

### Progressive Earning Table

| Tier | Spend Range | Rate |
|------|-------------|------|
| 1 | RM 0 - 50 | 1 point/RM |
| 2 | RM 51 - 100 | 1.2 points/RM |
| 3 | RM 101 - 200 | 1.5 points/RM |
| 4 | RM 201+ | 2 points/RM |

### Category Rate Table

| Category | Rate |
|----------|------|
| Food & Beverage | 2 points/RM |
| Fashion & Apparel | 1 point/RM |
| Groceries | 1.5 points/RM |
| Electronics | 0.5 points/RM |
| Services | 1 point/RM |

### Time-Based Promotion Table

| Day | Rate |
|-----|------|
| Monday - Thursday | 1 point/RM |
| Friday | 1.5 points/RM |
| Weekend | 2 points/RM |
| Public Holiday | 3 points/RM |

## Table Rate Priority

When multiple tables apply, priority determines which rate is used:
- Higher priority tables are evaluated first
- First matching table is applied
- Default table serves as fallback

## Managing Table Rates

### Editing a Table

1. Click **Edit** on the table
2. Modify rates or conditions
3. Save changes

### Deleting a Table

1. Click **Delete** on the table
2. Confirm deletion

{% hint style="warning" %}
Deleting active table rates affects ongoing transactions. Ensure alternative rates exist before deletion.
{% endhint %}

### Activating/Deactivating

Toggle the status to activate or deactivate a table without deleting it.

## Best Practices

{% hint style="tip" %}
**Clear Structure:**
- Keep table structures simple
- Avoid overlapping conditions
- Document all rate tables
- Test thoroughly before activation
{% endhint %}

{% hint style="info" %}
**Promotional Rates:**
For temporary promotions:
1. Create new table with promotion rates
2. Set appropriate date range
3. Set higher priority than default
4. Table automatically expires after end date
{% endhint %}

{% hint style="warning" %}
**Gap Prevention:**
Ensure no gaps exist in spending ranges:
- Good: 0-50, 51-100, 101+
- Bad: 0-50, 55-100, 101+ (gap at 51-54)
{% endhint %}

## Integration with Other Features

Table rates work with:
- **Rank Multipliers** - Table rate × tier multiplier
- **Campaign Bonuses** - Can stack with promotional campaigns
- **Category Settings** - Category-specific rates

## Related Topics

- [Point Configuration](point-configuration.md)
- [Rank Settings](../customer-modules/rank-settings.md)
- [Campaigns](../campaigns/README.md)
