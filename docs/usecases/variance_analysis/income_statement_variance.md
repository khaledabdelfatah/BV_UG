# **Income Statement Variance Analysis**

The Income Statement – Variance Analysis tab provides a detailed financial comparison across time periods to support performance monitoring and business analysis. This view is designed to help users quickly identify fluctuations in key metrics such as Net Profit, Operating Profit, Revenue, and Expenses using both Month-over-Month (MoM) and Year-over-Year (YoY) comparisons.

!!! example "Income Statement Variance Analysis Tab"
    <iframe frameborder="0" style="width:100%;height:402px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=variance%20analysis.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1boAfeICqUWMp7-mrhR322AkArNduqgbW%26export%3Ddownload"></iframe>

## **Available Filters**

The dashboard provides several filtering options for data refinement:

- **Year**: Select the reporting year (e.g., 2025).

- **Month**: Choose a specific month to analyze (e.g., April).

- **Dim Account Type**: Filter by account categories such as Revenue, Expenses, Assets, Liabilities, and Equity. By default, all account types are included.

### **Changing Threshold Values**

The top control panel includes configurable threshold fields to customize variance highlighting:

- **Income Value**  
    Enter an absolute amount (e.g., `1,000 SAR`). Variances equal to or greater than this value will be considered for highlighting.

- **Income Percentage**  
    Specify a percentage (e.g., `10%`). Variances equal to or greater than this percentage of the previous period’s value will be considered.

!!! info "Highlighting Criteria"
    Both conditions must be met for a variance to be highlighted:
    - The variance is **greater than or equal to** the specified **Income Value**.
    - The variance is **greater than or equal to** the specified **Income Percentage** of the previous period's value.

#### **Example**

Suppose the previous period value is `5,000 SAR` and you set:

- **Income Value** = `1,000 SAR`
- **Income Percentage** = `10%`

Then:

- The minimum absolute variance is `1,000 SAR`.
- The minimum percentage-based variance is `500 SAR` (`10% of 5,000 SAR`).

A variance must exceed **both** `1,000 SAR` and `500 SAR` to be highlighted.

---

- **Income Value 2**  
    An additional field for an alternative absolute threshold (e.g., `2,000 SAR`). This can be used independently or for advanced filtering scenarios.

---

#### **Applying Thresholds**

1. Configure the desired threshold values.
2. Click the **Update** button (highlighted in pink).
3. The dashboard will refresh, and variances meeting the criteria will be highlighted using conditional formatting (e.g., red fill for large negative swings).

## **Table Structure and Columns**

The data table displays financial performance across three dimensions:

- Current Period (e.g., April 2025)

- Previous Period (e.g., March 2025)

- Same Period Last Year (e.g., April 2024)

Each row corresponds to a financial account category. Users can expand or collapse account hierarchies to analyze subcategories in more detail.

### **Column Definitions** 

| **Column**                         | **Description**                                                                                                                                                                                                                                           |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Account**                        | Displays a hierarchical structure of financial accounts grouped under major categories such as Net Profit, Operating Profit, Revenue, and Expenses. Accounts can be expanded to view sub-accounts (e.g., Cost of Services, Depreciation). |
| **Balance**                        | The actual financial value recorded for the selected month (e.g., April 2025). Expressed in SAR.                                                                 |
| **Balance PP** *(Previous Period)* | The value recorded for the same account in the **prior month** (e.g., March 2025). Used for **MoM comparison** to assess recent changes.                                                                                                                  |
| **Variance PP**                    | The difference between the current and previous month's balances: `Balance - Balance PP`. <br>**Positive** values may indicate improvement (e.g., increased revenue or reduced costs). **Negative** values signal deterioration.                          |
| **% of Change PP**                 | Percentage difference between current and previous month: `(Variance PP / Balance PP) × 100`. Useful for identifying sudden changes. Large negative values are color-coded in red to highlight areas needing attention.                                   |
| **Current Balance**                | This column shows the current balance for the selected period (Same as Balance)                                                                                               |
| **Balance PY** *(Previous Year)*   | The value for the same account in the **same month of the previous year** (e.g., April 2024). Used for **YoY comparison** to track annual changes.                                                                                                        |
| **Variance PY**                    | The difference between the current balance and last year’s balance: `Balance - Balance PY`. A **positive variance** generally indicates improved performance over the year.                                                                               |
| **% of Change PY**                 | Percentage difference between current and previous year’s value: `(Variance PY / Balance PY) × 100`. This metric reveals long-term trends. |

!!! tip "**Note on Monthly and Yearly Comparisons**"
    - Month-over-Month (MoM): Compares financial performance of the current month against the previous month (e.g., April 2025 vs. March 2025). Useful for short-term trend analysis and operational monitoring.
    - Year-over-Year (YoY): Compares the current month’s data against the same month in the prior year (e.g., April 2025 vs. April 2024). Useful for seasonal trend tracking and longer-term performance evaluation.