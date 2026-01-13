# Add Rank

Learn how to create new membership tiers in the Loyalty CRM system.

## Overview

Adding a new rank allows you to expand your loyalty program's tier structure to better segment and reward your customers.

## Accessing Add Rank

Navigate to **Customer > Rank Settings > Add Rank**

## Creating a New Rank

### Step 1: Access the Add Rank Form

Click the **Add Rank** or **Create New Rank** button from the Rank Settings page.

### Step 2: Configure Basic Information

| Field | Description | Example |
|-------|-------------|---------|
| **Rank Name** | Display name for the tier | Gold Member |
| **Rank Code** | Internal identifier | GOLD |
| **Description** | Brief tier description | Premium membership tier |
| **Status** | Active/Inactive | Active |

### Step 3: Set Qualification Criteria

| Field | Description |
|-------|-------------|
| **Minimum Points** | Points required to qualify |
| **Maximum Points** | Upper limit (for next tier) |
| **Spending Threshold** | Minimum spend to qualify |
| **Evaluation Period** | Time frame for qualification |

### Step 4: Configure Benefits

| Setting | Description |
|---------|-------------|
| **Point Multiplier** | Earning rate multiplier (e.g., 1.5x) |
| **Exclusive Rewards** | Tier-specific redemption options |
| **Special Discounts** | Tier-based pricing |
| **Priority Access** | Early access to promotions |

### Step 5: Set Retention Rules

| Setting | Description |
|---------|-------------|
| **Validity Period** | How long tier status is maintained |
| **Review Period** | When tier status is re-evaluated |
| **Grace Period** | Buffer before downgrade |
| **Retention Points** | Points needed to maintain tier |

### Step 6: Visual Configuration

| Setting | Description |
|---------|-------------|
| **Rank Color** | Color associated with tier |
| **Rank Icon/Image** | Visual representation |
| **Card Design** | Digital card appearance |

### Step 7: Save the Rank

Click **Save** to create the new rank.

## Example Rank Configuration

### Gold Tier Example

```
Rank Name: Gold Member
Rank Code: GOLD
Minimum Points: 5,000
Maximum Points: 14,999
Point Multiplier: 1.5x
Validity: 12 months
Review Period: Annual
Benefits:
- 10% discount on rewards
- Early access to promotions
- Birthday double points
- Free gift wrapping
```

## Validation Rules

{% hint style="info" %}
**System Validation:**
- Rank codes must be unique
- Point ranges cannot overlap with existing ranks
- Multiplier must be greater than 0
{% endhint %}

## Best Practices

{% hint style="tip" %}
**Tier Planning:**
- Plan your entire tier structure before creating ranks
- Ensure point thresholds create natural progression
- Consider your customer base demographics
{% endhint %}

{% hint style="warning" %}
**Point Ranges:**
Ensure no gaps or overlaps exist between tier point ranges:
- Bronze: 0 - 999
- Silver: 1,000 - 4,999
- Gold: 5,000 - 14,999
- Platinum: 15,000+
{% endhint %}

## After Creating a Rank

Once created:
1. The rank appears in the Rank Settings list
2. Customers meeting criteria are automatically assigned
3. Benefits become available to qualifying members
4. Reports will include the new tier

## Related Topics

- [Rank Settings](rank-settings.md)
- [Edit/Delete Rank](edit-delete-rank.md)
- [Point Configuration](../main-settings/point-configuration.md)
