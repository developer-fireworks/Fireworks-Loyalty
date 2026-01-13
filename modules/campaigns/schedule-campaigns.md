# Schedule Campaigns

Create and manage time-scheduled campaigns in the Loyalty CRM system.

## Overview

Schedule Campaigns allow you to plan and automate campaigns to run at specific times without manual intervention.

## Accessing Schedule Campaigns

Navigate to **Campaigns > Schedule Campaign List**

## Schedule Campaign List

| Column | Description |
|--------|-------------|
| Campaign Name | Title |
| Schedule | Timing configuration |
| Status | Active/Scheduled/Completed |
| Next Run | Upcoming execution |
| Actions | Edit/Delete/View |

## Creating a Scheduled Campaign

### Step 1: Access Create Form

Click **Create Schedule Campaign**.

### Step 2: Campaign Details

| Field | Description |
|-------|-------------|
| **Name** | Campaign title |
| **Description** | Campaign details |
| **Type** | Campaign type |

### Step 3: Schedule Configuration

| Setting | Description |
|---------|-------------|
| **Start Date** | When to begin |
| **End Date** | When to stop |
| **Frequency** | Daily/Weekly/Monthly |
| **Time** | Specific execution time |
| **Timezone** | Time zone for scheduling |

### Step 4: Campaign Actions

Define what happens at scheduled time:
- Send notifications
- Award points
- Distribute vouchers
- Trigger workflows

### Step 5: Save and Activate

Click **Save** to schedule the campaign.

## Schedule Types

### One-Time Schedule

```
Date: January 15, 2026
Time: 10:00 AM
Action: Send promotional email
```

### Recurring Daily

```
Time: 9:00 AM daily
Action: Send daily digest
```

### Recurring Weekly

```
Day: Every Monday
Time: 8:00 AM
Action: Weekly promotion reminder
```

### Recurring Monthly

```
Day: 1st of every month
Action: Monthly statement email
```

## Best Practices

{% hint style="tip" %}
- Schedule campaigns during optimal engagement times
- Test scheduling with non-critical campaigns first
- Monitor scheduled campaigns regularly
{% endhint %}

{% hint style="warning" %}
**Timezone Awareness:**
Ensure you understand the system timezone to schedule campaigns at the intended local time.
{% endhint %}

## Related Topics

- [Create Campaign](create-campaign.md)
- [Communications](../communications/README.md)
