# Create Campaign

Learn how to create marketing campaigns in the Loyalty CRM system.

## Overview

Create targeted campaigns to engage members and drive loyalty program participation.

## Accessing Campaign Creation

Navigate to **Campaigns > Cron Campaign List > Create Campaign**

## Campaign Creation Steps

### Step 1: Basic Information

| Field | Description |
|-------|-------------|
| **Campaign Name** | Descriptive title |
| **Campaign Code** | Unique identifier |
| **Description** | Campaign details |
| **Campaign Type** | Select type |
| **Status** | Active/Inactive |

### Step 2: Schedule Configuration

| Field | Description |
|-------|-------------|
| **Start Date** | When campaign begins |
| **End Date** | When campaign ends |
| **Frequency** | One-time/Recurring |
| **Schedule** | Specific timing (if recurring) |

### Step 3: Target Audience

| Setting | Description |
|---------|-------------|
| **All Members** | Target entire membership |
| **Audience List** | Select specific segments |
| **Tier Filter** | Target specific ranks |
| **Custom Criteria** | Advanced filtering |

### Step 4: Campaign Actions

Define what happens when campaign conditions are met:

| Action Type | Description |
|-------------|-------------|
| **Award Points** | Credit bonus points |
| **Send Notification** | Push/Email/SMS |
| **Issue Voucher** | Distribute rewards |
| **Upgrade Tier** | Automatic promotion |

### Step 5: Campaign Conditions

Set triggers for the campaign:

| Condition | Example |
|-----------|---------|
| **Transaction Based** | Spend RM100 or more |
| **Visit Based** | 5th visit in month |
| **Product Based** | Purchase specific items |
| **Time Based** | Birthday month |

### Step 6: Save and Activate

Review configuration and click **Save** to create the campaign.

## Campaign Types Explained

### Points Bonus Campaign

```
Trigger: Transaction above RM50
Action: Award 100 bonus points
Duration: Weekend only
```

### Birthday Campaign

```
Trigger: Member's birthday month
Action: Issue birthday voucher + double points
Duration: Entire birthday month
```

### Engagement Campaign

```
Trigger: No purchase in 60 days
Action: Send re-engagement offer
Duration: Continuous
```

### New Member Campaign

```
Trigger: New registration
Action: Welcome bonus points
Duration: First 30 days
```

## Campaign Configuration Options

### Notification Settings

| Setting | Options |
|---------|---------|
| **Notification Type** | Push/Email/SMS/All |
| **Send Time** | Immediate/Scheduled |
| **Template** | Select message template |

### Reward Settings

| Setting | Options |
|---------|---------|
| **Points Amount** | Fixed or calculated |
| **Voucher Type** | Select voucher |
| **Quantity Limit** | Maximum per member |
| **Validity** | Reward expiration |

### Frequency Controls

| Setting | Options |
|---------|---------|
| **Once Per Member** | Single reward |
| **Daily Limit** | Max per day |
| **Campaign Limit** | Total budget cap |
| **Tier Limit** | Per tier restrictions |

## Testing Campaigns

{% hint style="tip" %}
**Before Launch:**
1. Create test with limited audience
2. Verify triggers work correctly
3. Confirm rewards are distributed
4. Check notifications are sent
5. Review campaign reports
{% endhint %}

## Managing Campaigns

### Editing a Campaign

1. Navigate to campaign list
2. Click **Action > Edit**
3. Modify settings
4. Save changes

### Pausing/Stopping

1. Click **Action > Edit**
2. Change status to Inactive
3. Save

### Duplicating

Use existing campaigns as templates:
1. Click **Action > Duplicate**
2. Modify for new campaign
3. Save with new name

## Best Practices

{% hint style="info" %}
**Clear Objectives:**
Define what success looks like:
- Increased transactions
- Higher engagement
- New member acquisition
- Retention improvement
{% endhint %}

{% hint style="warning" %}
**Budget Control:**
Always set limits to control costs:
- Maximum rewards per member
- Total campaign budget
- Daily/weekly caps
{% endhint %}

## Related Topics

- [Campaigns Overview](README.md)
- [Promotion Rules](promotion-rules.md)
- [Daily Check-In Reward](daily-checkin-reward.md)
- [Communications](../communications/README.md)
