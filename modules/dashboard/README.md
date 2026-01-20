# Dashboard

The Dashboard provides an eagle-eye view of your Loyalty CRM system, displaying key metrics and insights at a glance.

## Overview

Once logged in, the Dashboard is your central hub for monitoring the health and performance of your loyalty program.

## Dashboard Components

The dashboard displays the following key metrics:

<figure><img src="../../.gitbook/assets/unknown (3).png" alt=""><figcaption></figcaption></figure>

### Customer Metrics

| Metric            | Description                          |
| ----------------- | ------------------------------------ |
| **New Customers** | Number of new customer registrations |
| **User Sessions** | Active user sessions in the system   |
| **Active**        | Currently active members             |
| **Expired**       | Members with expired status          |

### Points & Transactions

| Metric                  | Description                      |
| ----------------------- | -------------------------------- |
| **Total Points**        | Aggregate points in the system   |
| **Top Redeemer**        | Members with highest redemptions |
| **Top Gain Points**     | Members earning the most points  |
| **Latest Transactions** | Recent transaction activity      |

### Business Metrics

| Metric               | Description                     |
| -------------------- | ------------------------------- |
| **Total Merchants**  | Number of registered merchants  |
| **Best Seller**      | Top-performing rewards/products |
| **Best Category**    | Most popular reward categories  |
| **Low on Inventory** | Items requiring restocking      |

## Analytics & Reports

Access detailed analytics and reporting features through the dashboard menu:

| Report Module | Description | Documentation |
| ------------- | ----------- | ------------- |
| **[Purchase by Branch](dashboard-module.md#purchase-by-branch)** | View purchase history by branch location with timeline visualization | [View Details](dashboard-module.md#purchase-by-branch) |
| **[Rank Tier Movement](dashboard-module.md#rank-tier-movement)** | Track member rank tier changes and distribution over time | [View Details](dashboard-module.md#rank-tier-movement) |
| **[Rank vs Gender](dashboard-module.md#rank-vs-gender)** | Analyze demographic composition by rank tier and gender | [View Details](dashboard-module.md#rank-vs-gender) |
| **[Sales by Brands](dashboard-module.md#sales-by-brands)** | Monitor sales performance across tenant brands | [View Details](dashboard-module.md#sales-by-brands) |
| **[Voucher Redemption](dashboard-module.md#voucher-redemption)** | Track voucher redemption patterns and trends | [View Details](dashboard-module.md#voucher-redemption) |

{% hint style="info" %}
**Complete Dashboard Module Documentation:** For comprehensive guides on each analytics feature, including step-by-step instructions, data fields, and use cases, see the [Dashboard Module Documentation](dashboard-module.md).
{% endhint %}

## Date Filters

Filter dashboard data by different time periods:

| Filter           | Description                                         |
| ---------------- | --------------------------------------------------- |
| **Today**        | View data from the current day                      |
| **Yesterday**    | View data from the previous day                     |
| **Last 7 Days**  | View data from the past week                        |
| **Last 30 Days** | View data from the past month                       |
| **Custom Date**  | Select a specific date range using From & To fields |

### Using Custom Date Filter

1. Select the **From** date
2. Select the **To** date
3. Click **Submit** to apply the filter

## Dashboard Navigation

From the dashboard, you can quickly access:

* **Overview** - Return to main dashboard view
* **[Analytics Reports](dashboard-module.md)** - Detailed reporting modules
* **Customer Modules** - Manage customer data
* **Reports** - Generate detailed reports
* **Campaigns** - View active campaigns

## Best Practices

{% hint style="info" %}
**Daily Monitoring:**

* Check "Low on Inventory" alerts daily
* Review "Latest Transactions" for anomalies
* Monitor "New Customers" for growth trends
* Track [Voucher Redemption](dashboard-module.md#voucher-redemption) patterns
{% endhint %}

{% hint style="info" %}
**Quick Analysis:** Use the date filters to compare performance across different time periods and identify trends. See [Dashboard Module](dashboard-module.md) for advanced analytics.
{% endhint %}

{% hint style="success" %}
**Advanced Analytics:** Explore the [Dashboard Module](dashboard-module.md) for in-depth analysis including:
- Branch performance comparison
- Member tier progression tracking
- Demographic insights
- Brand sales analytics
- Voucher effectiveness measurement
{% endhint %}

## Related Topics

* [Dashboard Module (Analytics)](dashboard-module.md) - Detailed reporting and analytics
* [Reports Overview](../reports/)
* [Customer Management](../customer-modules/)
* [Campaigns](../campaigns/)

## Quick Links

### Analytics & Reporting
- [Purchase by Branch →](dashboard-module.md#purchase-by-branch)
- [Rank Tier Movement →](dashboard-module.md#rank-tier-movement)
- [Rank vs Gender →](dashboard-module.md#rank-vs-gender)
- [Sales by Brands →](dashboard-module.md#sales-by-brands)
- [Voucher Redemption →](dashboard-module.md#voucher-redemption)

### Documentation
- [Complete Dashboard Module Guide →](dashboard-module.md)
- [Common Dashboard Features →](dashboard-module.md#common-dashboard-features)
- [Troubleshooting →](dashboard-module.md#troubleshooting)
```

## Key Changes Made:

1. **Added "Analytics & Reports" section** - New table linking to all 5 dashboard module features
2. **Updated "Dashboard Navigation"** - Added link to Analytics Reports
3. **Enhanced "Best Practices"** - Added reference to Voucher Redemption tracking
4. **New hint box** - Added "Advanced Analytics" tip linking to the dashboard module
5. **Updated "Related Topics"** - Added Dashboard Module as the first link
6. **Added "Quick Links" section** - Easy navigation to all analytics features and documentation

## Navigation Structure:
```
README.md (Dashboard Overview)
    ├─→ dashboard-module.md (Main Analytics Documentation)
    │   ├─→ #purchase-by-branch
    │   ├─→ #rank-tier-movement
    │   ├─→ #rank-vs-gender
    │   ├─→ #sales-by-brands
    │   └─→ #voucher-redemption
    └─→ Other related sections