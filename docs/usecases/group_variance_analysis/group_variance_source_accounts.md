# Group Variance Analysis – Source Accounts

The **Source Accounts** tab provides a detailed, account-level breakdown of movements and variances across the STC Group. This view is essential for financial analysts and auditors who need to perform drill-down investigations, reconciliations, and trace variances back to their originating accounts.

All accounts displayed here are **leaf-level accounts**—the most granular accounts in the hierarchy. This tab helps users identify the root causes of group-level variances by linking them directly to their respective source accounts.

!!! example "Group Variance – Source Accounts"
    <iframe frameborder="0" style="width:100%;height:498px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=group_variance_analysis.drawio&page-id=soTpT0AmZtzUCZYpx9Oi&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1tykHKd6UvIqKrMuQW2qPkYfQKrK2jlD-%26export%3Ddownload"></iframe>

## **Balance Comparison Table**

Each row in the table represents a source account and includes the following columns:

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

### **Threshold Filters**

- Use **Variance Value** and **% of Change** together to filter results.
- Alternatively, enter a **Variance Value 2** to apply a single, stricter filter.

The purpose of the Source Accounts tab is to link group accounts with their subsidiary accounts, enabling users to pinpoint the source of variances at the group level.

---

## **Drill-Through Functionality**

For any **KSA account**, right-click and select **Drill Through → DB KSA JE Transactions** to view the detailed journal entries that contributed to the variance. This feature allows you to trace financial data back to its source, helping to explain discrepancies or unusual movements.

To download the DB KSA JE Transactions data, click the **Download CSV** button. The data will be saved in CSV format for further analysis in Excel or any spreadsheet application.

!!! example "Drill Through DB KSA JE Transactions"
    <iframe frameborder="0" style="width:100%;height:538px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=group_variance_analysis.drawio&page-id=PBaoNtj3UZR1JrrFW4Xe&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1tykHKd6UvIqKrMuQW2qPkYfQKrK2jlD-%26export%3Ddownload"></iframe>

---

### **Account Root Cause Analysis**

To identify the root cause of a variance for a KSA account:

1. Right-click the **% of Change** column for the desired account.
2. Select **Drill Through → Account Root Cause**.

This displays:
- The top 3 companies contributing to the variance,
- The top function,
- The top product impacting the variance.

> **Note:** This feature is available only for KSA accounts.

!!! example "Drill Through Account Root Cause"
    <iframe frameborder="0" style="width:100%;height:495px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Variance%20Analysis%20v2.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D11uIfu6aBCtmK_znVgfw3Np24ADaPW90e%26export%3Ddownload"></iframe>

---

### **Group Account Variance Root Cause**

To analyze the variance root cause for a main group account:

1. Right-click the group account.
2. Select **Drill Through → Variance Root Cause 1**.

You will see:
- The top 3 subsidiary accounts contributing to the variance,
- For each subsidiary, the top 3 sub-accounts,
- The percentage impact of each subsidiary and sub-account.

!!! example "Drill Through Variance Root Cause 1"
    <iframe frameborder="0" style="width:100%;height:443px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Variance%20Analysis%20v2.drawio&page-id=PDhnAYqNNjWR8YlZQjnD&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D11uIfu6aBCtmK_znVgfw3Np24ADaPW90e%26export%3Ddownload"></iframe>

---

### **Additional Drill-Through Options**

- **Balance Column:** Right-click a balance value, select **Drill Through → DB KS JE Transactions** to view related journal entries.
- **Current Balance Column:** Right-click a current balance value, select **Drill Through → KSA JE Transactions** to see the journal entries contributing to the current balance.

!!! example "Drill Through KSA JE Transactions"
    <iframe frameborder="0" style="width:100%;height:577px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Variance%20Analysis%20v2.drawio&page-id=IeAZHWzYyCo6KKTABH9c&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D11uIfu6aBCtmK_znVgfw3Np24ADaPW90e%26export%3Ddownload"></iframe>


By leveraging these features, users can efficiently trace, analyze, and explain variances at both the group and account levels, ensuring transparency and accuracy in financial reporting.