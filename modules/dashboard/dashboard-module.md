# Dashboard Module

## Overview

The Dashboard module provides comprehensive analytics and reporting capabilities for the Fireworks Loyalty system. It offers multiple visualization views to track purchase history, member rank movements, gender demographics, sales by brands, and voucher redemption statistics.

**Demo Note:** For demonstration purposes, the current date is set to 31 March 2022, with 30 days of data availability.

## Table of Contents

- [Purchase by Branch](#purchase-by-branch)
- [Rank Tier Movement](#rank-tier-movement)
- [Rank vs Gender](#rank-vs-gender)
- [Sales by Brands](#sales-by-brands)
- [Voucher Redemption](#voucher-redemption)

---

## Purchase by Branch

### Description

View and analyze purchase history data organized by branch location with timeline visualization.

### Features

- **Branch Distribution Visualization**: Interactive pie chart showing purchase distribution across branches
- **Timeline Analysis**: Line graph displaying purchase history movement over time
- **Multi-Branch Support**: Track data across multiple locations (Johor, Kuala Lumpur, Shah Alam)
- **Flexible Date Filtering**: Quick filters and custom date range selection
- **Detailed Transaction View**: Comprehensive transaction-level data

### Date Range Options

- **Today**: Current day's data
- **Yesterday**: Previous day's data
- **Last 7 days**: Rolling 7-day window
- **Last 30 days**: Rolling 30-day window
- **Custom Range**: User-defined from/to dates

### Data Displayed

#### Purchase History By Branch (Pie Chart)
Visualizes the distribution of purchases across different branch locations:
- Johor
- Kuala Lumpur
- Shah Alam

#### Purchase History Movement Timeline (Line Graph)
Shows purchase trends over time with the following metrics:
- **Fireworks Mall**: Primary shopping mall purchases
- **Fws Johor Bahru**: Johor Bahru branch purchases
- **Fws Shah Alam**: Shah Alam branch purchases
- **Total**: Aggregate purchases across all branches

#### Detailed Transaction Table

| Column | Description |
|--------|-------------|
| **Member ID** | Unique identifier for the member |
| **Receipt ID** | Transaction receipt number |
| **Receipt Date** | Date of purchase (YYYY-MM-DD) |
| **Receipt Time** | Time of purchase (HH:MM:SS) |
| **Phone** | Member contact number |
| **Cost** | Transaction amount |
| **Mall** | Branch/mall location |
| **Points Release** | Loyalty points awarded |
| **Points Float** | Pending/floating points |

### How to Access

1. Navigate to **Dashboard**
2. Select **Purchase by Branch**
3. Choose desired date range filter or set custom dates
4. Click **Submit** to generate report

### Example Use Cases

- Monitor branch performance over time
- Identify peak purchase periods
- Compare sales across different locations
- Track member transaction patterns
- Analyze points distribution by branch

---

## Rank Tier Movement

### Description

Track and analyze member rank tier changes and distribution over time. This report helps monitor loyalty program engagement and member progression through different tiers.

### Features

- **Rank Distribution Visualization**: Pie chart showing current distribution across all tiers
- **Flexible Date Filtering**: Quick preset options and custom date ranges
- **Tier Tracking**: Monitor movement between Platinum, Silver, Tourist, and Gold tiers
- **Historical Analysis**: Compare tier distributions across different time periods

### Rank Tiers

The loyalty program includes four membership tiers:

1. **Platinum**: Premium tier members
2. **Gold**: High-value members
3. **Silver**: Standard members
4. **Tourist**: Entry-level members

### Date Range Options

- **Today**: Current day's tier distribution
- **Yesterday**: Previous day's snapshot
- **Last 7 days**: Weekly tier movement
- **Last 30 days**: Monthly tier analysis
- **Custom Range**: Specify from/to dates

### Data Displayed

#### Rank Tier Summary (Pie Chart)
Visual representation showing:
- Distribution percentage across all tiers
- Color-coded tier segments
- Member count per tier

#### Report Date Range
Displays the selected date range in format: `YYYY-MM-DD to YYYY-MM-DD`

### How to Access

1. Navigate to **Dashboard**
2. Select **Rank Tier Movement**
3. Choose a date range:
   - Click quick filters (Today, Yesterday, Last 7 days, Last 30 days), OR
   - Enter custom dates in **From** and **To** fields
4. Click **Submit** to generate report

### Example Workflow

```
1. Click "Last 30 days" button
2. Click "Submit"
3. View Rank Tier Summary chart showing distribution
4. Analyze tier percentages and member counts
```

### Use Cases

- Monitor member tier progression
- Identify trends in tier upgrades/downgrades
- Evaluate loyalty program effectiveness
- Plan targeted marketing campaigns by tier
- Track the impact of promotions on tier movement

---

## Rank vs Gender

### Description

Comprehensive demographic analysis combining member rank tiers with gender distribution. This report provides insights into the composition of your loyalty program membership across different segments.

### Features

- **Dual Visualization**: Both gender and rank distribution charts
- **Cross-Tabulation**: Detailed breakdown of gender by rank tier
- **Demographic Insights**: Understand member composition
- **Total Aggregation**: Grand totals for all dimensions

### Data Categories

#### Gender Categories
- **Male**: Male members
- **Female**: Female members
- **Unspecified**: Members who haven't specified gender

#### Rank Tiers
- **Silver**: Standard tier
- **Gold**: High-value tier
- **Platinum**: Premium tier
- **Tourist**: Entry-level tier

### Visualizations

#### 1. Gender Distribution (Pie Chart)
Shows the overall gender breakdown:
- Male percentage and count
- Female percentage and count
- Unspecified percentage and count

#### 2. Rank Distribution (Pie Chart)
Displays rank tier composition:
- Silver members
- Gold members
- Platinum members
- Tourist members

#### 3. Horizontal Bar Chart
Stacked bar visualization showing:
- Gender distribution within each rank tier
- Comparative view across all tiers
- Scale: 0 to 250 members

### Summary Table

| Rank | Male | Female | Unspecified | Total Members |
|------|------|--------|-------------|---------------|
| Silver | 55 | 36 | 45 | 136 |
| Gold | 12 | 12 | 0 | 24 |
| Platinum | 16 | 5 | 1 | 22 |
| Tourist | 12 | 7 | 0 | 19 |
| **Grand Total** | **95** | **60** | **46** | **201** |

*Note: The table above shows example data from the demo system*

### How to Access

1. Navigate to **Dashboard**
2. Select **Rank VS Gender**
3. Click **View** to display the report

### Key Insights

#### From the Example Data:
- **Silver tier** is the largest segment with 136 members (67.7%)
- **Male members** represent 47.3% of total membership
- **Female members** account for 29.9% of membership
- **Unspecified gender** comprises 22.9% of membership
- **Platinum tier** has the highest male-to-female ratio (16:5)
- **Gold tier** shows equal gender distribution (12:12)

### Use Cases

- **Targeted Marketing**: Design gender-specific campaigns by tier
- **Product Strategy**: Tailor offerings based on demographic composition
- **Membership Analysis**: Identify underrepresented segments
- **Diversity Tracking**: Monitor gender balance across tiers
- **Campaign Effectiveness**: Evaluate demographic impact of promotions
- **Resource Allocation**: Optimize service offerings by segment

---

## Sales by Brands

### Description

Analyze sales performance across different tenant brands within the loyalty program network. This report helps track which brands are driving the most transactions and revenue.

### Features

- **Brand Performance Tracking**: Monitor sales by individual brands/tenants
- **Visual Analytics**: Charts and graphs for easy interpretation
- **Multi-Tenant Support**: Track all participating brands in one view

### How to Access

1. Navigate to **Dashboard**
2. Select **Sales By Brands**
3. Click **View** to display the sales analysis

### Data Scope

**Demo Configuration:**
- Report date set to: **31 March 2022**
- Data availability: **30 days**

### Expected Data Views

While the specific visualizations may vary, typical displays include:
- Sales volume by brand
- Revenue distribution across tenants
- Transaction count per brand
- Comparative performance metrics

### Use Cases

- **Tenant Performance**: Evaluate individual brand contribution
- **Revenue Analysis**: Identify top-performing brands
- **Partnership Decisions**: Make data-driven tenant partnership decisions
- **Space Allocation**: Optimize mall space based on brand performance
- **Marketing Strategy**: Focus promotions on high-performing brands
- **Tenant Relations**: Share performance data with brand partners

### Integration

This module works in conjunction with:
- **Purchase by Branch**: Cross-reference location with brand performance
- **Voucher Redemption**: Track brand-specific voucher usage
- **Member Analytics**: Understand which brands attract which member segments

---

## Voucher Redemption

### Description

Comprehensive tracking and analysis of voucher redemption patterns across the loyalty program. This report provides insights into voucher usage, popular offers, and redemption trends over time.

### Features

- **Redemption Visualization**: Pie chart showing top voucher redemptions
- **Flexible Date Filtering**: Multiple time range options
- **Voucher Type Analysis**: Breakdown by voucher category and value
- **Trend Tracking**: Monitor redemption patterns over time

### Voucher Types Tracked

The system monitors various voucher categories:

1. **RM5 e-Coupon (Sign-on Rewards)**: Welcome incentive for new members
2. **RM5 e-Coupon (Supermarket)**: Grocery shopping discounts
3. **RM20 e-Coupon (1st Purchase Rewards)**: First-time purchase incentive
4. **RM5 Flat Rate Parking (1st Purchase Rewards)**: Parking benefit voucher
5. **Others**: Additional voucher types

### Date Range Options

- **Today**: Current day's redemptions
- **Yesterday**: Previous day's activity
- **Last 7 days**: Weekly redemption pattern
- **Last 30 days**: Monthly redemption analysis
- **Custom Range**: User-defined date range (from/to)

### Data Displayed

#### Top Vouchers Redemption Summary (Pie Chart)
Visual breakdown showing:
- Distribution of redemptions by voucher type
- Percentage share for each voucher category
- Redemption count per voucher type
- Color-coded segments for easy identification

#### Date Range Display
Shows the active report period in format: `DD/MM/YYYY to DD/MM/YYYY`

Example: `01/03/2022 to 31/03/2022`

### How to Access

1. Navigate to **Dashboard**
2. Select **Vouchers Redemption**
3. Choose a date range:
   - **Quick Filters**: Click Today, Yesterday, Last 7 days, or Last 30 days
   - **Custom Range**: 
     - Enter **From** date
     - Enter **To** date
4. Click **Submit** to generate report

### Step-by-Step Guide

#### Viewing Last 30 Days:
```
1. Click "Last 30 days" button
2. Click "Submit"
3. View Top Vouchers Redemption Summary chart
```

#### Viewing Last 7 Days:
```
1. Click "Last 7 days" button
2. Click "Submit"
3. Analyze weekly redemption patterns
```

#### Viewing Yesterday:
```
1. Click "Yesterday" button
2. Click "Submit"
3. Review previous day's redemptions
```

#### Viewing Today:
```
1. Click "Today" button
2. Click "Submit"
3. Monitor real-time redemption activity
```

#### Custom Date Range:
```
1. Click "From date" field
2. Enter start date (e.g., 01/03/2022)
3. Click "To date" field
4. Enter end date (e.g., 31/03/2022)
5. Click "Submit"
6. View redemptions for custom period
```

### Example Data Insights

Based on the demo system, typical redemption patterns include:

- **Sign-on Rewards** (RM5 e-Coupon): Popular with new members
- **Supermarket Vouchers** (RM5 e-Coupon): High-frequency redemption
- **First Purchase Rewards** (RM20 e-Coupon): Strong conversion driver
- **Parking Vouchers** (RM5 Flat Rate): Valued convenience benefit

### Use Cases

#### For Marketing Teams:
- **Campaign Effectiveness**: Measure voucher promotion success
- **Offer Optimization**: Identify most attractive voucher types
- **Budget Planning**: Forecast redemption rates for future campaigns
- **Member Engagement**: Track which offers drive member activity

#### For Operations:
- **Inventory Management**: Plan voucher stock based on redemption trends
- **Partner Coordination**: Share redemption data with participating merchants
- **Capacity Planning**: Anticipate demand for voucher-related services

#### For Strategy:
- **ROI Analysis**: Calculate return on voucher investments
- **Member Behavior**: Understand redemption patterns by segment
- **Program Design**: Design effective voucher structures
- **Competitive Analysis**: Benchmark against industry standards

### Best Practices

1. **Regular Monitoring**: Check redemption rates weekly
2. **Trend Analysis**: Compare month-over-month patterns
3. **Segmentation**: Cross-reference with member tiers and demographics
4. **Expiration Tracking**: Monitor voucher expiration to minimize waste
5. **A/B Testing**: Test different voucher values and types
6. **Seasonal Adjustments**: Adapt voucher offerings to seasonal demand

### Integration with Other Modules

- **Purchase by Branch**: See which branches have highest redemption
- **Rank Tier Movement**: Analyze redemption by member tier
- **Sales by Brands**: Track brand-specific voucher usage

---

## Common Dashboard Features

### Universal Date Filtering

All dashboard reports support consistent date filtering:

```
[Today] [Yesterday] [Last 7 days] [Last 30 days]

From: [DD/MM/YYYY]  To: [DD/MM/YYYY]  [Submit]
```

### Navigation Structure

```
Dashboard
├── Rank Tier Movement
├── Vouchers Redemption
├── Sales By Brands
├── Purchase by Branch
├── Rank VS Gender
└── Campaign Communications
```

### Data Refresh

- Reports are generated on-demand when **Submit** is clicked
- Date range changes require clicking **Submit** to update
- All visualizations update simultaneously

### Visualization Types

The dashboard employs multiple visualization methods:

1. **Pie Charts**: For distribution and proportion analysis
2. **Line Graphs**: For timeline and trend analysis
3. **Bar Charts**: For comparative analysis
4. **Data Tables**: For detailed transaction-level views

### Export and Sharing

While not explicitly shown in the documentation, typical dashboard implementations support:
- Report exporting (PDF, Excel)
- Data download for further analysis
- Scheduled report generation
- Email distribution

---

## Technical Notes

### Demo Environment

- Current system date: **31 March 2022**
- Data availability: **30 days** rolling window
- URL: `https://demo.fireworksmedia.com/loyalty/index.php/en/admin/home`

### System Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Minimum screen resolution: 1024x768
- Active admin account with dashboard permissions

### Performance Considerations

- Large date ranges may take longer to process
- Custom date ranges spanning multiple months may timeout
- Recommend using preset filters for faster results
- Consider breaking large analyses into smaller date ranges

---

## Troubleshooting

### Report Not Loading

1. Verify you clicked the **Submit** button
2. Check that date range is valid (From date before To date)
3. Ensure dates are within the available data window
4. Try using a preset filter instead of custom dates
5. Refresh the page and try again

### No Data Displayed

1. Confirm the selected date range contains transactions
2. Verify your account has permission to view the data
3. Check if filters are too restrictive
4. Try expanding the date range
5. Contact system administrator if issue persists

### Visualizations Not Rendering

1. Enable JavaScript in your browser
2. Clear browser cache and cookies
3. Try a different browser
4. Disable browser extensions that might interfere
5. Check browser console for error messages

---

## Security and Permissions

### Access Control

Dashboard access is restricted to users with appropriate permissions:
- Admin users: Full access to all dashboard reports
- Manager users: Limited to specific reports
- Staff users: May have read-only access

### Data Privacy

- All reports respect data privacy regulations
- Personal information (phone numbers) visible only to authorized users
- Aggregated reports anonymize member data
- Audit trails track who accesses which reports

---

## Future Enhancements

Potential upcoming features:
- Real-time dashboard updates
- Predictive analytics
- Custom report builder
- Advanced filtering options
- Mobile-responsive design
- API access for external integrations
- Automated email reports
- Comparative period analysis (YoY, MoM)

---

## Support

For assistance with the Dashboard module:
- **Documentation**: Refer to this guide
- **Technical Support**: Contact your system administrator
- **Feature Requests**: Submit via the feedback channel
- **Bug Reports**: Use the issue tracking system

---

## Changelog

### Current Version (Demo)
- Purchase by Branch reporting
- Rank Tier Movement tracking
- Rank vs Gender demographics
- Sales by Brands analysis
- Voucher Redemption monitoring
- Multiple date range filters
- Interactive visualizations

---

*Last Updated: Based on demo system dated 31 March 2022*
*Demo URL: https://demo.fireworksmedia.com/loyalty/index.php/en/admin/home*
