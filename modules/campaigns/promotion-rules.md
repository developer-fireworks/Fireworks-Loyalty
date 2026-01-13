# Promotion Rules

Configure point multipliers and bonus rules for promotional campaigns.

## Overview

Promotion Rules define special earning rates and bonuses that apply during promotional periods or for specific conditions.

## Accessing Promotion Rules

Navigate to **Campaigns > Promotion Rules**

## Promotion Rules List

The list displays all configured rules:

| Column | Description |
|--------|-------------|
| Rule Name | Promotion title |
| Type | Multiplier/Bonus/Both |
| Multiplier | Point multiplier value |
| Status | Active/Inactive |
| Period | Start and end dates |
| Actions | Edit/Delete |

## Creating a New Rule

### Step 1: Access Create Form

Click **Create New Rule** from the Promotion Rules page.

### Step 2: Basic Configuration

| Field | Description |
|-------|-------------|
| **Rule Name** | Descriptive title |
| **Rule Code** | Unique identifier |
| **Description** | Rule explanation |
| **Status** | Active/Inactive |

### Step 3: Define Rule Type

| Type | Description |
|------|-------------|
| **Point Multiplier** | Multiply points by X |
| **Bonus Points** | Add fixed bonus |
| **Both** | Multiplier + bonus |

### Step 4: Set Conditions

| Condition | Options |
|-----------|---------|
| **Date Range** | When rule applies |
| **Day of Week** | Specific days |
| **Time of Day** | Specific hours |
| **Transaction Amount** | Minimum/maximum spend |
| **Category** | Specific product categories |
| **Tenant** | Specific merchants |
| **Member Tier** | Specific membership levels |

### Step 5: Configure Merchants

| Setting | Description |
|---------|-------------|
| **All Merchants** | Apply to all |
| **Select Merchants** | Choose specific tenants |
| **Exclude Merchants** | Exclude specific tenants |

### Step 6: Save the Rule

Click **Save** to create the promotion rule.

## Editing Rules

### Step 1: Access Edit

Click **Action > Edit** on the rule.

### Step 2: Modify Settings

Update any configuration settings as needed.

### Step 3: Save Changes

Click **Save** to apply modifications.

## Activating Merchants

### Edit Activate Merchant

1. Navigate to the promotion rule
2. Click **Edit Activate Merchant**
3. Select merchants to include/exclude
4. Save changes

## Rule Examples

### Double Points Weekend

```
Name: Weekend Double Points
Type: Multiplier
Multiplier: 2x
Condition: Saturday & Sunday
All Merchants: Yes
```

### Birthday Bonus

```
Name: Birthday Triple Points
Type: Multiplier
Multiplier: 3x
Condition: Member's birthday month
Duration: Entire month
```

### Category Promotion

```
Name: F&B Extra Points
Type: Bonus
Bonus: 50 points
Condition: F&B category transactions
Minimum Spend: RM 30
```

### Tenant-Specific Promotion

```
Name: Merchant Launch Promo
Type: Both
Multiplier: 1.5x
Bonus: 100 points
Merchants: Selected only
Duration: 1 week
```

## Rule Priority

When multiple rules could apply:
1. Most specific rules apply first
2. Highest multiplier is used (not stacked, unless configured)
3. Bonuses may stack (depending on configuration)

## Best Practices

{% hint style="tip" %}
**Clear Communication:**
- Announce promotions to members
- Display active promotions prominently
- Clarify terms and conditions
{% endhint %}

{% hint style="info" %}
**Strategic Timing:**
- Align with business objectives
- Consider competitive landscape
- Balance frequency and impact
{% endhint %}

{% hint style="warning" %}
**Cost Management:**
- Calculate potential liability
- Set budget limits
- Monitor actual vs projected
{% endhint %}

## Reporting

Track promotion performance:
- Points awarded under each rule
- Transaction volume impact
- Participating merchants
- Member engagement

## Related Topics

- [Campaigns Overview](README.md)
- [Create Campaign](create-campaign.md)
- [Point Configuration](../main-settings/point-configuration.md)
- [Campaign Reports](../reports/campaign-reports.md)
