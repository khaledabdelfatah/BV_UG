# **Variance Analysis**

This dashboard provides a comprehensive view of variance analysis, allowing users to compare current and previous periods, analyze variances, and visualize trends over time.


## **Filter Controls**

At the top of the dashboard, users can apply filters to narrow the scope of analysis:

- **Year:** Select the reporting year.

- **Month:** Choose the month of interest.

- **Dim Account Type:** Filter by account type (e.g., bank, equity, liability).

- **Account:** Choose specific account(s) to analyze.

### **Filter Table Data**

You can also filter the table data by clicking on the filter name in the table header and selecting the desired values from the dropdown menu. This allows for quick adjustments to the displayed data.

## **Changing Threshold Values**

You can customize the thresholds that determine when a variance is considered significant. This allows you to highlight only the variances that matter most to your analysis.

### **Threshold Types**

- **Variance Value:** Set a minimum absolute difference (e.g., `1,000 SAR`).  
- **Percentage Value:** Set a minimum percentage change (e.g., `10%` of the previous period's value).

Both thresholds must be exceeded for a variance to be highlighted. For example, if the previous period value is `5,000 SAR` and you set:

- **Variance Value:** `1,000 SAR`
- **Percentage Value:** `10%`

A variance will be highlighted only if:

- The absolute difference is greater than `1,000 SAR`, **and**
- The percentage change is greater than `10%`

#### **Example**

| Previous Period Value | Variance Value | Percentage Value | Highlighted? |
|----------------------|---------------|-----------------|--------------|
| 5,000 SAR            | 1,200 SAR     | 12%             | ✅           |
| 5,000 SAR            | 900 SAR       | 18%             | ❌           |
| 5,000 SAR            | 1,200 SAR     | 8%              | ❌           |

### **Additional Threshold**

- **Variance Value 2:** Optionally, set a second absolute threshold (e.g., `2,000 SAR`) for advanced filtering or alternative highlighting scenarios.

!!! tip "Adjusting Thresholds"
    Use the dashboard controls to set or update these thresholds at any time. This helps you focus on the most relevant variances for your analysis.

## **Column Definitions**

| **Column**           | **Description**                                                                                                                                                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **GS Group**         | The highest-level grouping for financial accounts. Each GS Group can be expanded to reveal its related FS Groups and sub-accounts, helping to organize accounts into major financial sections.                                     |
| **FS Group**         | A sub-group within a GS Group that further categorizes accounts into logical sections for detailed analysis.                                                                               |
| **Account**          | Represents individual financial accounts, organized hierarchically under GS and FS Groups. Accounts can be expanded to show sub-accounts (e.g., Cost of Services, Depreciation).                                                |
| **Balance**          | The actual financial value recorded for the selected month (e.g., April 2025), expressed in SAR.                                                                                          |
| **Balance PP**<br>*Previous Period* | The value for the same account in the previous month (e.g., March 2025). Used for Month-over-Month (MoM) comparison to assess recent changes.                                                        |
| **Variance PP**      | The difference between the current and previous month's balances: `Balance - Balance PP`. Positive values may indicate improvement (e.g., increased revenue or reduced costs); negative values signal deterioration.              |
| **% of Change PP**   | The percentage change from the previous month: `(Variance PP / Balance PP) × 100`. Large negative values are highlighted to draw attention to significant declines.                                                              |
| **Current Balance**  | Displays the current balance for the selected period (identical to the Balance column).                                                                                                   |
| **Balance PY**<br>*Previous Year* | The value for the same account in the same month of the previous year (e.g., April 2024). Used for Year-over-Year (YoY) comparison to track annual changes.                                         |
| **Variance PY**      | The difference between the current balance and last year’s balance: `Balance - Balance PY`. A positive variance generally indicates improved performance over the year.                                                         |
| **% of Change PY**   | The percentage change from the previous year: `(Variance PY / Balance PY) × 100`. This metric highlights long-term trends.                                                                |

!!! tip "Changing Column Order"
    You can rearrange the columns by dragging and dropping them to customize your view. This allows you to prioritize the most relevant data for your analysis.