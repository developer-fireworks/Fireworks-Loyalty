# Reward Claim Limit

Configure redemption limits and restrictions for rewards.

## Overview

Reward Claim Limits allow you to control how many times members can redeem specific rewards.

## Accessing Claim Limits

Claim limits are configured within **Reward Management** when creating or editing rewards.

## Types of Claim Limits

| Limit Type | Description |
|------------|-------------|
| **Per Member Lifetime** | Total ever per member |
| **Per Member Daily** | Maximum per day |
| **Per Member Weekly** | Maximum per week |
| **Per Member Monthly** | Maximum per month |
| **Total Inventory** | Overall quantity |
| **Per Transaction** | Maximum per order |

## Configuring Claim Limits

### Step 1: Edit Reward

Navigate to **Rewards Module > Reward Management** and edit the reward.

### Step 2: Set Limits

| Field | Example |
|-------|---------|
| **Member Lifetime Limit** | 2 per member |
| **Daily Limit** | 1 per day |
| **Weekly Limit** | 2 per week |
| **Monthly Limit** | 4 per month |

### Step 3: Save Configuration

Click **Save** to apply limits.

## Limit Scenarios

### High-Value Reward

```
Monthly Limit: 1
Lifetime Limit: 2
Reason: Control cost, ensure fairness
```

### Popular Item

```
Daily Limit: 1
Monthly Limit: 3
Reason: Prevent stockouts, share availability
```

### Promotional Reward

```
Lifetime Limit: 1
Total Inventory: 500
Reason: One per customer, limited supply
```

## Limit Hierarchy

Limits are checked in order:
1. Total inventory available?
2. Member lifetime limit reached?
3. Monthly limit reached?
4. Weekly limit reached?
5. Daily limit reached?

First failed check prevents redemption.

## Error Messages

When limits are reached, members see:
- "Daily limit reached - try again tomorrow"
- "You've already claimed this reward"
- "This reward is currently unavailable"

## Best Practices

{% hint style="tip" %}
**Fair Distribution:**
Use limits to ensure rewards are available to more members rather than being claimed by a few.
{% endhint %}

{% hint style="info" %}
**Clear Communication:**
Display limit information on reward pages so members understand restrictions before attempting to redeem.
{% endhint %}

{% hint style="warning" %}
**Balanced Limits:**
Limits that are too restrictive can frustrate members. Find the right balance for your program.
{% endhint %}

## Related Topics

- [Reward Management](reward-management.md)
- [Pending Rewards](pending-rewards.md)
- [Rewards Reports](../reports/rewards-reports.md)
