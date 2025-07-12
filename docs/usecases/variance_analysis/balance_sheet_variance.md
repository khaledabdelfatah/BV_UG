# Balance Sheet 

The **Balance Sheet** dashboard enables users to compare asset balances across three time periods, providing clear insights into month-over-month and year-over-year changes. This view is designed for:

- **Finance teams** monitoring account trends
- **Auditors** validating data consistency
- **Managers** identifying significant or unusual changes

---

## **Screen Elements**

### **Time Selection Controls**

At the top center, use the **Year** and **Month** selectors to define the reporting period. For example, selecting *April 2025* displays:

- **Current Balance:** April 2025
- **Previous Period:** March 2025
- **Previous Year:** April 2024

---

### **Balance Comparison Table**

Each account row displays the following columns:

| Column              | Description                                              |
|---------------------|----------------------------------------------------------|
| **Balance**         | Balance for the selected month (e.g., April 2025)        |
| **Balance pp**      | Balance from the previous month (March 2025)             |
| **Variance pp**     | Difference between current and previous month            |
| **% of Change**     | Percentage change from previous period                   |
| **Current Balance** | Same as "Balance" (may appear again depending on layout) |
| **Balance py**      | Balance from the same month last year (April 2024)       |
| **Variance py**     | Difference between current and previous year             |
| **% of Change**     | Year-over-year percentage change                         |

---

### **Filter Panel**

Use the filter panel to refine your view by:

- **Function**
- **Company**
- **Network**
- **Customer**
- **Account**
- **Project**
- **Product**

You can also set threshold limits:

- **Sheet Value:** Show only changes above a specified amount (e.g., > $10M)
- **Sheet Percentage:** Show only changes above a specified percentage (e.g., > 10%)

These filters help you focus on high-impact variances.

---
## **Using the Dashboard**

1. **Select the Month and Year** to analyze.
2. **Apply filters** to focus on specific teams, projects, or products.
3. **Review variance columns:**
    - Identify large negative values (typically highlighted in red).
    - Compare both percentage and absolute value changes.
4. **Drill down** into accounts with unusual or unexpected variances.

---

## **Data Refresh**

Data is refreshed regularly. Check the **timestamp** in the top right corner (e.g., *19-JUN-2025 06:43*) to ensure you are viewing the latest data.

---

## **Customizing Balance Highlight Thresholds**

You can control which variances are highlighted by setting threshold values, allowing you to focus on the most significant changes.

### **Threshold Options**

There are two main threshold types:

- **Sheet Value:** Minimum absolute difference (e.g., `1,000 SAR`) required to highlight a record.
- **Sheet Percentage:** Minimum percentage change (e.g., `10%`) required to highlight a record.

By default, **both** thresholds must be exceeded for a value to be highlighted:

- The absolute difference is greater than the Sheet Value **and**
- The percentage change is greater than the Sheet Percentage

#### Example

| Previous Period Value | Variance Value | Percentage Value | Highlighted? |
|----------------------|---------------|-----------------|--------------|
| 5,000 SAR            | 1,200 SAR     | 12%             | ✅           |
| 5,000 SAR            | 900 SAR       | 18%             | ❌           |
| 5,000 SAR            | 1,200 SAR     | 8%              | ❌           |

### **Advanced: Second Variance Threshold**

- **Sheet Value 2:** Optionally, set a second absolute threshold (e.g., `2,000 SAR`) for advanced filtering or alternative highlighting rules.

!!! tip "Adjusting Thresholds"
     Use the dashboard controls to set or update thresholds at any time. This helps you quickly refine which values are highlighted, ensuring you see only the most relevant changes.

## **Benefits**

- Highlights only the most important changes, saving time.
- Automates period-to-period comparisons, reducing manual effort.
- Supports financial consistency and accountability.