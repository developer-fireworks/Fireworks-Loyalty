# Purchase by Branch

## Overview

View and analyze purchase history data organized by branch location with timeline visualization. This report provides comprehensive insights into transaction patterns across different branch locations.

## Features

- **Branch Distribution Visualization**: Interactive pie chart showing purchase distribution across branches
- **Timeline Analysis**: Line graph displaying purchase history movement over time
- **Multi-Branch Support**: Track data across multiple locations (Johor, Kuala Lumpur, Shah Alam)
- **Flexible Date Filtering**: Quick filters and custom date range selection
- **Detailed Transaction View**: Comprehensive transaction-level data

## Date Range Options

- **Today**: Current day's data
- **Yesterday**: Previous day's data
- **Last 7 days**: Rolling 7-day window
- **Last 30 days**: Rolling 30-day window
- **Custom Range**: User-defined from/to dates

## Data Displayed

### Purchase History By Branch (Pie Chart)

Visualizes the distribution of purchases across different branch locations:
- **Johor**: Transactions from Johor branch
- **Kuala Lumpur**: Transactions from Kuala Lumpur branch
- **Shah Alam**: Transactions from Shah Alam branch

The pie chart provides:
- Visual percentage breakdown
- Color-coded segments for each branch
- Transaction count per location
- Easy comparison of branch performance

### Purchase History Movement Timeline (Line Graph)

Shows purchase trends over time with the following metrics:

| Metric | Description |
|--------|-------------|
| **Fireworks Mall** | Primary shopping mall purchases |
| **Fws Johor Bahru** | Johor Bahru branch purchases |
| **Fws Shah Alam** | Shah Alam branch purchases |
| **Total** | Aggregate purchases across all branches |

The timeline graph displays:
- Daily transaction trends
- Peak purchase periods
- Comparative performance across branches
- Historical purchase patterns

### Detailed Transaction Table

Access comprehensive transaction details with the following columns:

| Column | Description | Example |
|--------|-------------|---------|
| **Member ID** | Unique identifier for the member | 3270, 8431, 22428 |
| **Receipt ID** | Transaction receipt number | 4328528425, 4214289 |
| **Receipt Date** | Date of purchase | 2022-03-31 |
| **Receipt Time** | Time of purchase | 09:48:31, 10:13:55 |
| **Phone** | Member contact number | 60125581226 |
| **Cost** | Transaction amount (RM) | 51, 1845, 127 |
| **Mall** | Branch/mall location | Kuala Lumpur, Johor |
| **Points Release** | Loyalty points awarded | 0, 4 |
| **Points Float** | Pending/floating points | 51, 0, 145 |

**Example Data:**

```
Member: 3270
Receipt: 4328528425
Date: 2022-03-31 at 09:48:31
Cost: RM 51
Location: Kuala Lumpur
Points Released: 0
Points Float: 51
```

## How to Access

### Step-by-Step Guide

1. Navigate to **Dashboard** from the main menu
2. Click **Purchase by Branch** in the dashboard submenu
3. Select your desired date range:
   - Click a quick filter button (Today, Yesterday, Last 7 days, Last 30 days), OR
   - Enter custom dates in the **From** and **To** fields
4. Click **Submit** to generate the report

### Using Quick Filters

#### View Last 30 Days
```
1. Click "Last 30 days" button
2. Click "Submit"
3. View comprehensive monthly data
```

#### View Last 7 Days
```
1. Click "Last 7 days" button
2. Click "Submit"  
3. Analyze weekly trends
```

#### View Yesterday's Data
```
1. Click "Yesterday" button
2. Click "Submit"
3. Review previous day's performance
```

#### View Today's Data
```
1. Click "Today" button
2. Click "Submit"
3. Monitor real-time activity
```

### Using Custom Date Range

For specific date ranges:

1. Click the **From** date field
2. Select or enter start date (format: DD/MM/YYYY)
3. Click the **To** date field
4. Select or enter end date (format: DD/MM/YYYY)
5. Click **Submit** to generate the report

**Example:**
```
From: 01/03/2022
To: 31/03/2022
[Submit]
```

## Report Sections

### 1. Report Header

Displays the active date range:
```
Report Date: 2022-03-01 to 2022-03-31
```

### 2. Purchase History By Branch Chart

- Pie chart showing branch distribution
- Legend with branch names
- Percentage breakdown
- Transaction totals per branch

**Example Distribution:**
- Johor: 28 transactions
- Kuala Lumpur: 452 transactions
- Shah Alam: 19 transactions

### 3. Purchase History Movement Timeline

- Line graph with multiple data series
- X-axis: Date range
- Y-axis: Number of transactions
- Multiple colored lines for each branch
- Total aggregate line

**Timeline Features:**
- Hover over points for exact values
- Compare branch performance visually
- Identify peak transaction days
- Spot trends and patterns

### 4. Detailed Transaction List

Scrollable table showing:
- All transactions within date range
- Sortable columns
- Complete transaction details
- Member information
- Points allocation

## Use Cases

### For Operations Managers

**Monitor Branch Performance**
- Compare transaction volumes across locations
- Identify underperforming branches
- Allocate resources based on branch activity
- Track daily, weekly, and monthly trends

**Inventory Planning**
- Forecast inventory needs by branch
- Plan stock transfers between locations
- Optimize inventory levels based on transaction history

### For Marketing Teams

**Campaign Analysis**
- Measure campaign effectiveness by branch
- Identify which locations respond best to promotions
- Plan location-specific marketing initiatives
- Track promotion impact on transaction volume

**Customer Insights**
- Understand regional customer preferences
- Identify peak shopping times by location
- Design targeted offers for specific branches

### For Finance Teams

**Revenue Tracking**
- Monitor transaction values by branch
- Calculate revenue contribution per location
- Identify high-value transaction locations
- Track cost patterns across branches

**Points Management**
- Monitor points issuance by branch
- Track points float (pending points)
- Analyze points release patterns
- Manage points liability

### For Executive Leadership

**Strategic Decisions**
- Evaluate branch viability
- Make expansion decisions based on data
- Compare branch ROI
- Identify growth opportunities

**Performance Monitoring**
- Dashboard view of all branches
- Quick comparison of location performance
- Trend analysis for strategic planning

## Data Insights & Analysis

### Key Metrics to Track

1. **Total Transactions per Branch**
   - Indicates branch popularity
   - Shows customer traffic patterns
   - Helps with staffing decisions

2. **Average Transaction Value**
   - Calculate: Total Cost ÷ Number of Transactions
   - Identifies high-value locations
   - Guides pricing strategies

3. **Points Issuance Rate**
   - Tracks loyalty program engagement
   - Shows which branches drive loyalty
   - Helps optimize points strategy

4. **Peak Transaction Times**
   - Identifies busy periods
   - Guides staffing schedules
   - Optimizes operational hours

### Comparative Analysis

**Branch Performance Comparison:**
```
Kuala Lumpur: 452 transactions (High performer)
Johor: 28 transactions (Growing location)
Shah Alam: 19 transactions (New/Emerging)
```

**Timeline Pattern Analysis:**
- Identify seasonal trends
- Spot promotional impact
- Track growth trajectories
- Compare month-over-month changes

## Best Practices

{% hint style="success" %}
**Regular Monitoring**
- Review this report weekly to track branch performance
- Compare current period vs. previous period
- Set branch performance benchmarks
- Track improvement initiatives
{% endhint %}

{% hint style="info" %}
**Date Range Selection**
- Use "Last 30 days" for monthly reviews
- Use "Last 7 days" for weekly performance checks
- Use custom ranges for campaign analysis
- Compare same periods year-over-year
{% endhint %}

{% hint style="warning" %}
**Data Interpretation**
- Consider external factors (holidays, events, weather)
- Account for branch size differences
- Look at trends, not just absolute numbers
- Combine with other reports for complete picture
{% endhint %}

## Troubleshooting

### Report Not Loading

**Issue:** Report doesn't appear after clicking Submit

**Solutions:**
1. Verify you clicked the **Submit** button
2. Check that date range is valid (From date before To date)
3. Ensure dates are within the available data window
4. Try using a preset filter instead of custom dates
5. Refresh the page and try again
6. Check your internet connection

### No Data Displayed

**Issue:** Charts and tables are empty

**Solutions:**
1. Confirm the selected date range contains transactions
2. Verify your account has permission to view branch data
3. Check if filters are too restrictive
4. Try expanding the date range
5. Ensure transactions exist for the selected branches
6. Contact system administrator if issue persists

### Charts Not Rendering

**Issue:** Visualizations don't appear

**Solutions:**
1. Enable JavaScript in your browser
2. Clear browser cache and cookies
3. Try a different browser (Chrome, Firefox, Safari, Edge)
4. Disable browser extensions that might interfere
5. Check browser console for error messages
6. Verify browser meets minimum requirements

### Slow Performance

**Issue:** Report takes long to load

**Solutions:**
1. Reduce date range (try shorter periods)
2. Use quick filters instead of custom ranges
3. Clear browser cache
4. Check network connection speed
5. Try during off-peak hours
6. Contact IT if problem persists

## Export & Sharing

### Exporting Data

While viewing the report, you can typically:
- Print the report (browser print function)
- Take screenshots of visualizations
- Export transaction table data (if feature enabled)
- Generate PDF reports (if feature enabled)

### Sharing Reports

**Best Practices:**
- Schedule regular report distribution
- Share insights with relevant teams
- Create standardized report templates
- Document key findings
- Set up automated email reports (if available)

## Integration with Other Modules

### Related Reports

This report works in conjunction with:

- **[Rank vs Gender](rank-vs-gender.md)**: Cross-reference demographics with branch performance
- **[Sales by Brands](sales-by-brands.md)**: Analyze brand performance by branch
- **[Voucher Redemption](voucher-redemption.md)**: Track voucher usage by location
- **[Rank Tier Movement](rank-tier-movement.md)**: Understand member tier distribution by branch

### Data Flow

```
Purchase by Branch
    ↓
Provides transaction data
    ↓
Feeds into: Sales Analysis, Member Analytics, Points Management
    ↓
Supports: Strategic Planning, Operations, Marketing
```

## Technical Details

### Demo Environment

- **System Date**: 31 March 2022 (demo)
- **Data Availability**: 30 days rolling window
- **Update Frequency**: Real-time (production) / Static (demo)

### Data Refresh

- Reports generate on-demand when Submit is clicked
- Historical data available up to system retention period
- Real-time transaction data (in production environment)

### Browser Compatibility

**Supported Browsers:**
- Google Chrome 90+
- Mozilla Firefox 88+
- Safari 14+
- Microsoft Edge 90+

**Requirements:**
- JavaScript enabled
- Minimum screen resolution: 1024x768
- Cookies enabled
- Stable internet connection

## Security & Permissions

### Access Control

Access to this report requires:
- Active admin or manager account
- Dashboard view permissions
- Branch data access rights

### Data Privacy

- Member phone numbers visible only to authorized users
- Transaction data protected by role-based access
- Audit logs track report access
- Compliant with data privacy regulations

## Frequently Asked Questions

**Q: How often is the data updated?**
A: In production, data updates in real-time. The demo system shows static data from March 2022.

**Q: Can I export the transaction table?**
A: Export functionality depends on your system configuration. Check with your administrator.

**Q: Why do some transactions show 0 points released?**
A: Points may be in "float" status (pending) before release, or certain transaction types may not earn points.

**Q: How far back can I view historical data?**
A: Data availability depends on system retention policies. Typically 12-24 months of history is available.

**Q: Can I filter by specific branches?**
A: The current view shows all branches. Contact your administrator for custom filtered views.

**Q: What if I see discrepancies in the data?**
A: Verify the date range is correct, check for timezone differences, and contact support if issues persist.

## Additional Resources

- [Dashboard Overview](README.md)
- [Rank Tier Movement Report](rank-tier-movement.md)
- [Voucher Redemption Analysis](voucher-redemption.md)
- [Sales by Brands Report](sales-by-brands.md)

---

**Need Help?** Contact your system administrator or refer to the [Dashboard Overview](README.md) for general dashboard guidance.