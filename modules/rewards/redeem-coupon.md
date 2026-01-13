# Redeem Coupon

Process manual coupon redemptions at the point of service.

## Overview

Redeem Coupon allows staff to manually process coupon redemptions for members.

## Accessing Redeem Coupon

Navigate to **Rewards Module > Redeem Coupon**

## Manual Redemption Process

### Step 1: Access Redemption Screen

Navigate to the Redeem Coupon section.

### Step 2: Enter Coupon Details

| Field | Description |
|-------|-------------|
| **Coupon Code** | Voucher/coupon code |
| **Member ID** | Member identifier |
| **Scan Option** | Barcode/QR scanner |

### Step 3: Verify Coupon

System validates:
- Coupon existence
- Validity period
- Usage limits
- Member eligibility

### Step 4: Process Redemption

| Action | Description |
|--------|-------------|
| **Redeem** | Process the redemption |
| **Cancel** | Cancel operation |

### Step 5: Confirm Completion

Provide confirmation receipt/acknowledgment to member.

## Redemption Validation

The system checks:

| Validation | Description |
|------------|-------------|
| **Code Valid** | Coupon exists in system |
| **Not Expired** | Within validity period |
| **Not Used** | Available for use |
| **Member Match** | Belongs to correct member |
| **Location OK** | Valid at current location |

## Error Handling

| Error | Cause | Resolution |
|-------|-------|------------|
| Invalid Code | Typo or non-existent | Verify code entry |
| Expired | Past validity | Cannot redeem |
| Already Used | Previously redeemed | Check usage history |
| Wrong Location | Location restricted | Direct to valid location |

## Best Practices

{% hint style="tip" %}
**Staff Training:**
- Ensure staff know redemption process
- Train on error handling
- Practice validation procedures
{% endhint %}

{% hint style="info" %}
**Customer Communication:**
- Explain any restrictions clearly
- Provide alternative options if invalid
- Maintain positive interaction
{% endhint %}

## Related Topics

- [Pending Rewards](pending-rewards.md)
- [Reward Management](reward-management.md)
