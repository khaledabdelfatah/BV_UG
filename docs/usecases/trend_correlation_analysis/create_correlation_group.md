# **Creating Correlation Group**

The **Correlation Group** table allows users to configure key data points for trend and correlation analysis. Each row defines a correlation line composed of financial metrics, accounts, and subsidiaries used to generate meaningful visualizations and insights.

!!! example "Correlation Group Table"
    <iframe frameborder="0" style="width:100%;height:393px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%20%5BTrend%20and%20Correlation%20Analysis%5D.drawio&transparent=1&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1XAwCpOvDfJzAxYjEh6uuRbVFYETJhFhV%26export%3Ddownload" allowtransparency="true"></iframe>

## **Correlation Group Table Fields**

The following table outlines the fields available in the Correlation Group table.

| **Field**               | **Description**                                                                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Correlation Line**    | A unique incremental number assigned to each correlation entry. Helps in organizing and referencing correlation lines across the dashboard.       |
| **Correlation Item**    | A descriptive label for the correlation, typically a financial metric (e.g., Total Revenue, Capex). Appears in correlation charts for context.    |
| **Accounts**            | The consolidated account number associated with the correlation item. Used to pull relevant financial data.                                       |
| **Subsidiaries**        | Defines the company segment(s) involved in the correlation analysis (e.g., STC Kuwait, STC Bahrain).                                              |
| **Subsidiaries Accounts** | The specific account number from the selected subsidiary. Enables more granular analysis at the entity level.                                 |
| **PRA**                 | Short for *Prepayment Reconciliation Analysis*. Indicates whether the line includes PRA-related data. Options: **None** or **All PRA**.           |
| **Period Type**         | Determines the time period type for the data: either **YTD (Year-to-Date)** or **Periodic** (monthly/quarterly).                                 |
| **Negate**              | A toggle that reverses the sign of the metric, useful for inverse correlation (e.g., cost vs. revenue).                                           |
| **Exclude**             | Marks the correlation line as inactive without deletion. Useful for testing scenarios or temporarily disabling lines from the analysis.           |

---

### **Creating a Correlation Group**

1. **Access the Correlation Group Table**: Navigate to the Correlation Group table in your dashboard.
2. **Fill in the Fields**: Enter the relevant information for each field in a new row, including the correlation item, accounts, subsidiaries, and any other applicable data.
3. **Save Changes**: After filling in the necessary fields, save your changes by clicking on the "Create Correlation Group" button.
