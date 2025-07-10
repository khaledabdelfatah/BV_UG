# Group Variance Analysis - Profit & Loss

The **Group Variance Analysis – Profit & Loss** tab provides a detailed view of income and expense performance across the STC Group. This dashboard enables finance teams to:

- **Audit** internal financial records
- **Explain** material changes in P&L accounts
- **Support** monthly and yearly financial close processes
- **Detect** abnormal income or expense movements
- **Prepare** for executive-level financial reporting

This tab is essential for understanding shifts in key income statement metrics, such as revenue, operating income, and net income.

!!! example "Group Variance - Profit & Loss"
    <iframe frameborder="0" style="width:100%;height:492px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=group_variance_analysis.drawio&page-id=1pmbm4ulQHd663ALxY0E&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1tykHKd6UvIqKrMuQW2qPkYfQKrK2jlD-%26export%3Ddownload"></iframe>

## Controlling Variance Thresholds

### Accessing the Controls Panel

At the top-right corner of the dashboard, you will find three filter fields:

- **Variance Value**: Minimum absolute difference between periods.
- **% of Change Value**: Minimum percentage change between periods.
- **Variance Value 2**: Alternative single-value filter for large variances.

These controls help you quickly identify significant or unusual financial movements.

---

### How Filtering Works

You can filter the data using two different approaches:

#### **Option 1: Combine Variance Value AND % of Change Value**

- **Logic:** Both filters must be satisfied (AND logic).
- **Result:** An account is displayed only if:
    - The variance amount is **greater than or equal to** the value in **Variance Value**
    - The percentage change is **greater than or equal to** the value in **% of Change Value**

**Example:**

```
Variance Value = 200,000,000
% of Change Value = 10%
```
Only accounts with a **variance of at least 200M** _and_ a **change of at least 10%** will be shown.

---

#### **Option 2: Use Variance Value 2 Only**

- Entering a value in **Variance Value 2** disables the other two filters.
- Use this when you want to focus on accounts with a single, high variance threshold.

**Example:**

```
Variance Value 2 = 5,000,000,000
```
Only accounts with a **variance above 5B** will be displayed, regardless of percentage change.

---

### Applying Filters

As you adjust the filter values, the dashboard updates in real time to show only accounts that meet your criteria.

---

## Understanding the Balance Comparison Table

Each row in the table represents a financial account and includes the following columns:

| Column              | Description                                              |
|---------------------|---------------------------------------------------------|
| **Balance**         | Value for the selected month (e.g., April 2025)         |
| **Balance pp**      | Value from the previous month (e.g., March 2025)        |
| **Variance pp**     | Difference between current and previous month           |
| **% of Change**     | Percentage change from previous month                   |
| **Current Balance** | Same as "Balance" (may be repeated for layout reasons)  |
| **Balance py**      | Value from the same month last year (e.g., April 2024)  |
| **Variance py**     | Difference between current and previous year            |
| **% of Change**     | Year-over-year percentage change                        |

---

### Navigating and Sorting Accounts

- **Expand/Collapse:** Click the plus icon next to an account name to show or hide its sub-accounts. Sub-accounts will appear above the parent account by default.
- **Sorting and Totals:** To change how sub-accounts and totals are displayed:
    1. Select a column header.
    2. Right-click and choose one of the following:
        - **Show Totals Trailing:** Sub-accounts appear below the parent account; the parent is listed first.
        - **Show Totals Leading:** Sub-accounts appear above the parent account; the parent is listed last.

!!! example "Show Totals Trailing/Leading"
    <iframe frameborder="0" style="width:100%;height:512px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=group_variance_analysis.drawio&page-id=tQzzZA9eqVGRa3rge-n7&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1tykHKd6UvIqKrMuQW2qPkYfQKrK2jlD-%26export%3Ddownload"></iframe>