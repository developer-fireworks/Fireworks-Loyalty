# Point Configuration

Learn how to configure point earning and redemption rules in the Loyalty CRM system.

## Overview

Point Configuration defines how members earn and redeem points across your loyalty program.

## Accessing Point Configuration

Navigate to **Main Settings > Point Configuration**

## Configuration Areas

### Earning Configuration

| Setting | Description |
|---------|-------------|
| **Base Earning Rate** | Standard points per spend unit |
| **Minimum Transaction** | Minimum spend to earn points |
| **Points Rounding** | How points are rounded |
| **Earning Cap** | Maximum points per transaction |

### Redemption Configuration

| Setting | Description |
|---------|-------------|
| **Redemption Rate** | Points to value conversion |
| **Minimum Redemption** | Minimum points to redeem |
| **Maximum Redemption** | Maximum per transaction |
| **Redemption Restrictions** | Where/when redemption allowed |

### Expiration Configuration

| Setting | Description |
|---------|-------------|
| **Expiration Period** | How long points are valid |
| **Expiration Type** | Rolling/Fixed date |
| **Grace Period** | Warning period before expiry |
| **Notification Settings** | Expiry reminder rules |

## Configuring Earning Rules

### Step 1: Access Configuration

Navigate to Point Configuration settings.

### Step 2: Set Base Rates

| Field | Example | Description |
|-------|---------|-------------|
| **Points per RM** | 1 point | Base earning rate |
| **Minimum Spend** | RM 1.00 | Minimum to earn |
| **Rounding Rule** | Round down | How partial points handled |

### Step 3: Configure Multipliers

Set earning multipliers for:
- Member tiers (Gold: 1.5x, Platinum: 2x)
- Product categories
- Special promotions
- Time periods

### Step 4: Save Configuration

Click **Save** to apply settings.

## Earning Rules Examples

### Standard Configuration

```
Base Rate: 1 point per RM 1 spent
Minimum Transaction: RM 1
Silver Tier: 1.0x multiplier
Gold Tier: 1.5x multiplier
Platinum Tier: 2.0x multiplier
```

### Category-Based Configuration

```
F&B Category: 2 points per RM 1
Retail Category: 1 point per RM 1
Services: 1.5 points per RM 1
```

## Configuring Redemption Rules

### Redemption Rate

| Setting | Example |
|---------|---------|
| Points Value | 100 points = RM 1 |
| Minimum Redemption | 500 points |
| Maximum per Transaction | 50% of total |

### Redemption Restrictions

Configure where redemption is allowed:
- All outlets
- Specific tenants only
- Online only
- Exclusions (sale items, etc.)

## Point Expiration

### Rolling Expiration

Points expire X months after earning:
```
Expiration Period: 12 months from earn date
Grace Period: 30 days warning
```

### Fixed Date Expiration

All points expire on a specific date:
```
Expiration Date: December 31 annually
Grace Period: 60 days warning
```

## Best Practices

{% hint style="tip" %}
**Balanced Design:**
- Make earning achievable and rewarding
- Set redemption rates that are sustainable
- Provide clear value proposition
- Keep rules simple to understand
{% endhint %}

{% hint style="info" %}
**Communication:**
Always communicate point rules clearly to members:
- How to earn
- How to redeem
- Expiration policies
- Tier benefits
{% endhint %}

{% hint style="warning" %}
**Financial Impact:**
Point configuration directly affects:
- Program liability
- Customer perception of value
- Redemption costs
- Overall program ROI
{% endhint %}

## Testing Configuration

Before going live with changes:
1. Test earning scenarios
2. Test redemption scenarios
3. Verify tier multipliers
4. Check expiration calculations
5. Validate across all touchpoints

## Related Topics

- [Table Rate](table-rate.md)
- [Add/Minus Points](add-minus-points.md)
- [Rank Settings](../customer-modules/rank-settings.md)
- [Points Reports](../reports/points-reports.md)
