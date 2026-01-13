# Reward Management

Create and manage individual reward items in the Loyalty CRM system.

## Overview

Reward Management allows you to create, configure, and maintain the rewards available for member redemption.

## Accessing Reward Management

Navigate to **Rewards Module > Reward Management**

## Reward List View

| Column | Description |
|--------|-------------|
| Reward Name | Item title |
| Category | Assigned category |
| Points | Redemption cost |
| Inventory | Available quantity |
| Status | Active/Inactive |
| Actions | Edit/Delete/View |

## Creating a New Reward

### Step 1: Click Add Reward

Click **Add New Reward** or **Create Reward**.

### Step 2: Basic Information

| Field | Description | Required |
|-------|-------------|----------|
| **Reward Name** | Display title | Yes |
| **Reward Code** | Unique identifier | Yes |
| **Category** | Assign to category | Yes |
| **Description** | Detailed description | Yes |
| **Status** | Active/Inactive | Yes |

### Step 3: Point Configuration

| Field | Description |
|-------|-------------|
| **Points Required** | Redemption cost |
| **Cash + Points** | Combined redemption option |
| **Variable Points** | Range-based pricing |

### Step 4: Media Upload

| Field | Description |
|-------|-------------|
| **Main Image** | Primary product image |
| **Gallery** | Additional images |
| **Thumbnail** | List view image |

### Step 5: Inventory Settings

| Field | Description |
|-------|-------------|
| **Total Quantity** | Initial stock |
| **Track Inventory** | Enable stock tracking |
| **Low Stock Alert** | Alert threshold |
| **Out of Stock Action** | Hide/Show as unavailable |

### Step 6: Availability Settings

| Field | Description |
|-------|-------------|
| **Start Date** | When available |
| **End Date** | When expires |
| **Member Tiers** | Tier restrictions |
| **Store Locations** | Location restrictions |

### Step 7: Redemption Settings

| Field | Description |
|-------|-------------|
| **Redemption Type** | Instant/Approval required |
| **Fulfillment Type** | Pickup/Delivery/Digital |
| **Validity Period** | How long to claim |
| **Terms & Conditions** | Redemption rules |

### Step 8: Save Reward

Click **Save** to create the reward.

## Assigning Tenants to Rewards

### Step 1: Access Tenant Assignment

Navigate to reward and click **Assign Tenant** or edit the reward.

### Step 2: Select Tenants

| Option | Description |
|--------|-------------|
| **All Tenants** | Available at all locations |
| **Select Tenants** | Choose specific merchants |
| **Exclude Tenants** | Available everywhere except |

### Step 3: Save Assignment

Click **Save** to apply tenant settings.

## Setting Claim Limits

| Limit Type | Description |
|------------|-------------|
| **Per Member Total** | Maximum per member ever |
| **Per Member Daily** | Maximum per day |
| **Per Member Weekly** | Maximum per week |
| **Per Member Monthly** | Maximum per month |
| **Total Available** | Overall quantity limit |

## Editing Rewards

1. Click **Action > Edit** on the reward
2. Modify any fields
3. Click **Save**

## Deleting Rewards

1. Click **Action > Delete**
2. Confirm deletion

{% hint style="warning" %}
Consider deactivating instead of deleting to preserve historical data.
{% endhint %}

## Reward Types Configuration

### Physical Gift

```
Fulfillment: Pickup at store
Validity: 30 days to claim
Processing: Approval required
```

### E-Voucher

```
Fulfillment: Instant digital
Validity: 90 days to use
Processing: Instant
```

### Experience

```
Fulfillment: RSVP booking
Validity: Event date
Processing: Approval required
```

## Best Practices

{% hint style="tip" %}
**Reward Creation:**
- Use high-quality images
- Write clear descriptions
- Set appropriate point values
- Include terms and conditions
{% endhint %}

{% hint style="info" %}
**Inventory Management:**
- Set realistic stock levels
- Configure low stock alerts
- Plan for high-demand periods
{% endhint %}

{% hint style="warning" %}
**Value Alignment:**
Ensure point costs align with perceived value to maintain program credibility.
{% endhint %}

## Related Topics

- [Category Management](category-management.md)
- [Pending Rewards](pending-rewards.md)
- [Reward Claim Limit](reward-claim-limit.md)
- [Rewards Reports](../reports/rewards-reports.md)
