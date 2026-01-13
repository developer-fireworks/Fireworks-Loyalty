# Edit/Delete Rank

Learn how to modify or remove membership tiers in the Loyalty CRM system.

## Overview

Administrators can edit rank configurations or delete ranks that are no longer needed.

## Accessing Rank Management

Navigate to **Customer > Rank Settings**

## Editing a Rank

### Step 1: Locate the Rank

Find the rank you want to modify in the Rank Settings list.

### Step 2: Access Edit Mode

Click **Action > Edit** on the desired rank.

### Step 3: Modify Configuration

Update any of the following settings:

#### Basic Information
| Field | Description |
|-------|-------------|
| Rank Name | Display name |
| Rank Code | Internal identifier |
| Description | Tier description |
| Status | Active/Inactive |

#### Qualification Criteria
| Field | Description |
|-------|-------------|
| Minimum Points | Entry threshold |
| Maximum Points | Upper limit |
| Spending Threshold | Required spend |
| Evaluation Period | Assessment timeframe |

#### Benefits
| Field | Description |
|-------|-------------|
| Point Multiplier | Earning rate |
| Exclusive Rewards | Tier-specific rewards |
| Special Discounts | Tier discounts |

#### Retention Rules
| Field | Description |
|-------|-------------|
| Validity Period | Status duration |
| Review Period | Re-evaluation timing |
| Grace Period | Downgrade buffer |

### Step 4: Save Changes

Click **Save** to apply modifications.

## Deleting a Rank

### Step 1: Locate the Rank

Find the rank in the Rank Settings list.

### Step 2: Initiate Deletion

Click **Action > Delete** on the rank.

### Step 3: Confirm Deletion

Review the confirmation prompt and confirm the deletion.

{% hint style="danger" %}
**Warning: Impact of Deletion**

Deleting a rank affects:
- All members currently assigned to that rank
- Historical reporting data
- Associated benefits and rewards
- Automated tier assignment rules

**Members in a deleted rank will need to be reassigned to another tier.**
{% endhint %}

## Before Making Changes

### Impact Assessment

Consider the following before editing or deleting ranks:

| Action | Potential Impact |
|--------|------------------|
| Lowering point threshold | More members qualify, benefit costs increase |
| Raising point threshold | Members may be downgraded |
| Changing multiplier | Affects future earning rates |
| Removing benefits | Member satisfaction impact |
| Deleting rank | Members lose tier status |

### Communication Plan

{% hint style="info" %}
**Notify Affected Members:**
- Prepare communication before changes
- Explain reasons for changes
- Highlight any compensatory benefits
- Provide timeline for implementation
{% endhint %}

## Best Practices

{% hint style="tip" %}
**Before Editing:**
1. Document current configuration
2. Analyze member distribution
3. Calculate financial impact
4. Plan member communications
{% endhint %}

{% hint style="warning" %}
**Deactivate vs Delete:**
Consider setting a rank to Inactive instead of deleting to:
- Preserve historical data
- Allow easy reactivation
- Maintain reporting accuracy
{% endhint %}

## Handling Member Transitions

When deleting or significantly modifying a rank:

1. **Identify affected members** - Generate list of current rank members
2. **Define transition rules** - Determine new rank assignments
3. **Communicate changes** - Notify members in advance
4. **Execute transition** - Apply changes systematically
5. **Verify results** - Confirm correct reassignments

## Related Topics

- [Rank Settings](rank-settings.md)
- [Add Rank](add-rank.md)
- [Audience List](audience-list.md)
- [Communications](../communications/README.md)
