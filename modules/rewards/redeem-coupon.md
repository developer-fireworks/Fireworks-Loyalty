# Redeem Coupon

Process manual coupon redemptions at the point of service.

## Overview

Redeem Coupon allows staff to manually process coupon redemptions for members.

## Accessing Redeem Coupon

Navigate to Voucher > Redeem Coupon

## Manual Redemption Process

### Step 1: Access Redemption Screen

Navigate to the Redeem Coupon section.

### Step 2: Enter Coupon Details

| Field           | Description                                                              |
| --------------- | ------------------------------------------------------------------------ |
| **Coupon Code** | Enter the voucher or coupon code to be redeemed. This field is required. |

### Step 3: Verify Coupon

System validates:

* Coupon existence
* Validity period
* Usage limits
* Member eligibility

### Step 4: Process Redemption

| Action     | Description                                                                  |
| ---------- | ---------------------------------------------------------------------------- |
| **Redeem** | Click the Redeem button to submit the coupon code and process the redemption |
| **Cancel** | Cancel operation                                                             |

### Step 5: Confirm Completion

Provide confirmation receipt/acknowledgment to member.

## Redemption Validation

The system checks:

| Validation       | Description               |
| ---------------- | ------------------------- |
| **Code Valid**   | Coupon exists in system   |
| **Not Expired**  | Within validity period    |
| **Not Used**     | Available for use         |
| **Member Match** | Belongs to correct member |
| **Location OK**  | Valid at current location |

## Error Handling

| Error          | Cause                | Resolution               |
| -------------- | -------------------- | ------------------------ |
| Invalid Code   | Typo or non-existent | Verify code entry        |
| Expired        | Past validity        | Cannot redeem            |
| Already Used   | Previously redeemed  | Check usage history      |
| Wrong Location | Location restricted  | Direct to valid location |

## Best Practices

{% hint style="info" %}
**Staff Training:**

* Ensure staff know redemption process
* Train on error handling
* Practice validation procedures
{% endhint %}

{% hint style="info" %}
**Customer Communication:**

* Explain any restrictions clearly
* Provide alternative options if invalid
* Maintain positive interaction
{% endhint %}

## Related Topics

* [Pending Rewards](pending-rewards.md)
* [Reward Management](reward-management.md)
