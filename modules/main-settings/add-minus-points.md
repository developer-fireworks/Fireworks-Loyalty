# Add/Minus Points

Learn how to manually adjust member point balances in the Loyalty CRM system.

## Overview

The Add/Minus Points feature allows administrators to manually credit or debit points from member accounts.

<figure><img src="../../.gitbook/assets/unknown (17).png" alt=""><figcaption></figcaption></figure>

## Accessing Point Adjustment

Navigate to **Main Settings > Add / Minus Points**

## When to Use Manual Adjustments

| Scenario                      | Action       |
| ----------------------------- | ------------ |
| Customer complaint resolution | Add points   |
| Promotional bonus             | Add points   |
| Correction of errors          | Add or minus |
| Special rewards               | Add points   |
| Fraudulent activity           | Minus points |
| System errors                 | Add or minus |

## Making Point Adjustments

### Step 1: Select Member

Search for the member using:

* Member ID
* Email address
* Phone number
* Name

### Step 2: Choose Action

Select the adjustment type:

* **Add Points** - Credit points to account
* **Minus Points** - Debit points from account

### Step 3: Enter Details

| Field         | Description                   |
| ------------- | ----------------------------- |
| **Points**    | Number of points to adjust    |
| **Reason**    | Explanation for adjustment    |
| **Reference** | Ticket/case number (optional) |
| **Approval**  | Manager approval if required  |

### Step 4: Confirm and Submit

Review the adjustment details and click **Submit** or **Save**.

## Adjustment Form Fields

| Field                  | Description              | Required |
| ---------------------- | ------------------------ | -------- |
| **Member Selection**   | Search and select member | Yes      |
| **Adjustment Type**    | Add or Minus             | Yes      |
| **Point Amount**       | Number of points         | Yes      |
| **Reason/Description** | Justification for change | Yes      |
| **Effective Date**     | When adjustment applies  | No       |

## Approval Workflow

{% hint style="info" %}
**Approval Requirements:** Depending on your configuration, point adjustments may require:

* Manager approval for amounts above threshold
* Multi-level approval for large adjustments
* Audit documentation
{% endhint %}

## Audit Trail

All manual adjustments are logged with:

* Date and time
* Administrator who made the change
* Original and new balance
* Reason provided
* Approval chain (if applicable)

## Best Practices

{% hint style="info" %}
**Documentation:**

* Always provide clear, detailed reasons
* Reference support tickets when applicable
* Document customer communication
* Maintain consistency in adjustment policies
{% endhint %}

{% hint style="warning" %}
**Verification:** Before adjusting:

1. Verify member identity
2. Confirm current balance
3. Validate adjustment amount
4. Double-check before submitting
{% endhint %}

{% hint style="danger" %}
**Negative Balances:** The system may prevent adjustments that would result in negative point balances. Verify available balance before deducting points.
{% endhint %}

## Common Scenarios

### Goodwill Points

For customer service recovery:

```
Action: Add Points
Amount: 100 points
Reason: Goodwill gesture for delayed order - Ticket #12345
```

### Error Correction

For system/human errors:

```
Action: Add Points (or Minus Points)
Amount: Correct difference
Reason: Correction of order #67890 - Points not credited due to system error
```

### Promotional Bonus

For special promotions:

```
Action: Add Points
Amount: 500 points
Reason: Winner of August social media contest
```

## Related Topics

* [Point Configuration](point-configuration.md)
* [Points Reports](../reports/points-reports.md)
* [Customer Management](../customer-modules/)
