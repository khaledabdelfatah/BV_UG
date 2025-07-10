# Balance Sheet Variance Analysis

The **Group Variance Analysis – Balance Sheet** tab empowers finance teams to efficiently monitor and interpret changes in balance sheet accounts across the STC Group. This tool enhances financial oversight by enabling users to:

- **Audit** internal financial records for accuracy and compliance
- **Explain** significant movements in balance sheet line items
- **Support** both month-end and year-end closing activities
- **Identify** anomalies or potential accounting errors early

!!! example "Group Variance - Balance Sheet"
    <iframe frameborder="0" style="width:100%;height:608px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=group_variance_analysis.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1tykHKd6UvIqKrMuQW2qPkYfQKrK2jlD-%26export%3Ddownload"></iframe>

---

## Setting Variance Thresholds

### Accessing Filter Controls

At the top-right of the dashboard, you’ll find input fields for:

- **Variance Value**
- **% of Change Value**
- **Variance Value 2**

These controls let you focus on accounts with material or unusual changes.

---

### How Filtering Works

You can filter accounts using two approaches:

#### **Option 1: Combine Variance Value AND % of Change Value**

- **Logic:** Both conditions must be satisfied (AND logic).
- **Display:** An account appears only if:
    - The variance amount is **greater than or equal to** the **Variance Value**
    - The percentage change is **greater than or equal to** the **% of Change Value**

**Example:**

```
Variance Value = 200,000,000
% of Change Value = 10%
```
Only accounts with a **variance of at least 200M** _and_ a **change of at least 10%** will be shown.

---

#### **Option 2: Use Variance Value 2 Only**

- Entering a value in **Variance Value 2** overrides the other two fields.
- Use this for filtering based solely on a specific variance threshold.

**Example:**

```
Variance Value 2 = 5,000,000,000
```
Only accounts with a **variance above 5B** will be displayed, regardless of percentage change.

---

### Applying Filters

The dashboard updates in real time to display only accounts that meet your criteria.

---

## Understanding the Balance Comparison Table

Each account row includes the following columns:

| Column              | Description                                              |
|---------------------|---------------------------------------------------------|
| **Balance**         | Balance for the selected month (e.g., April 2025)       |
| **Balance pp**      | Balance from the previous month (e.g., March 2025)      |
| **Variance pp**     | Difference between current and previous month           |
| **% of Change**     | Percentage change from previous period                  |
| **Current Balance** | Same as "Balance" (may appear again depending on layout)|
| **Balance py**      | Balance from the same month last year (e.g., April 2024)|
| **Variance py**     | Difference between current and previous year            |
| **% of Change**     | Year-over-year percentage change                        |

---

You can expand or collapse each account to view sub-accounts by clicking the plus icon next to the account name. Expanding an account reveals its sub-accounts, displaying their respective balances and variances for deeper analysis.