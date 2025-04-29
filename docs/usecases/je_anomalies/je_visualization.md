
# Dashboard Components

## **Overview**

The "JE Anomalies Dashboard" consists of several components that provide insights into the data. The main components are:

- **Top 10 Categories by Number of Anomalies**: Highlights the categories with the highest anomaly counts.

- **Top 10 Sources by Number of Anomalies**: Shows the most common sources of anomalies.

- **Number of Anomalies by Value Risk**: Displays the distribution of anomalies based on their value risk (High, Medium, Low).

- **Detailed Anomalies Table**: Provides a comprehensive view of all detected anomalies, including their details and risk levels.

### **Enlarged View**

You can expand any chart or table for a clearer view:

1. Hover over a component (like a chart or table).

2. Click the enlarge icon that appears.

This opens the component in full-screen mode, making it easier to review details.
???+ example "Enlarge Icon"
    <iframe src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%202.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1Ln9LyxrZ2Z2kJ7HwHWBADKzALrPmS-aM%26export%3Ddownload" width="100%" height="400" style="border: none;"></iframe>

### **Exporting Data**
You can export tables or charts from the dashboard to Excel for further analysis or reporting.

**Steps to Export Data:**

1. Click on the table or chart you want to export.
2. A menu bar will appear at the top of the screen.
3. Click the Export icon.
4. A popup window will open with export options.

**Export Options:**

- **Single Excel File**: Exports all selected views into one Excel file. Each view will be placed in a separate sheet.
- **Multiple Excel Files**: Exports each view into its own Excel file.

Choose your preferred option, then click the **Export button**.

Wait a few seconds, your file will be downloaded automatically to your device.

???+ Example "Export Button"
    <iframe src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%202.drawio&page-id=yigNa85nCfERh74Zhj_U&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1Ln9LyxrZ2Z2kJ7HwHWBADKzALrPmS-aM%26export%3Ddownload" width="100%" height="400" style="border: none;"></iframe>

### **Formating Options**

You can apply different formatting styles to the data in tables or charts to improve readability or match reporting standards.

**Steps to Format Data:**

1. Click on the table or chart you want to format.
2. A menu bar will appear at the top of the screen.
3. Click the “Format Values” icon.
4. A dropdown menu will appear with several formatting options.
5. Select your desired format, the data will update immediately.

**Available Formatting Options:**

| **Format**                | **Description**                                                        | **Example**         |
|---------------------------|------------------------------------------------------------------------|---------------------|
| **General**               | Default format without styling.                                       | `12345.67`          |
| **Fixed**                 | Number with two decimal places.                                       | `12345.67`          |
| **Comma**                 | Adds thousands separator.                                              | `12,345.67`         |
| **Rounded**               | Rounds to the nearest whole number.                                    | `12,346`            |
| **Percentage**            | Converts number to a percentage.                                       | `12,345.67%`        |
| **Scientific**            | Scientific notation format.                                            | `1.234567E+4`       |
| **Accounting**            | Currency with alignment for accounting.                                | `$12,345.67`        |
| **Currency**              | Standard currency format.                                              | `$12,345.67`        |
| **Currency (Rounded)**    | Currency rounded to whole numbers.                                     | `$12,346.00`        |
| **Thousands (K)**         | Shortens numbers in thousands.                                         | `12.3K`             |
| **Millions (M)**          | Shortens numbers in millions.                                          | `12.3M`             |
| **Short Abbreviation**    | Auto-shortens numbers using K/M/B.                                     | `12.3K`             |
| **Date**                  | Formats as date.                                                       | `4/28/25`           |
| **Time**                  | Formats as time.                                                       | `4:04:00 PM`        |
| **Custom Format**         | Lets you enter your own custom format.                                | Custom input        |
| **Navigate with Minus Sign** | Shows negative values with a minus.                                 | `-12345.67`         |
| **Use Database Format**   | Keeps the original format from the database.      

---

## **Available Components**

### **Anomalies Table**

This table lists all detected anomalies with detailed metadata for each journal entry. Admin users can also interact with certain fields to help train the AI model.

| **Column Name**          | **Description** |
|--------------------------|-----------------|
| **Group Statement (CS) Group** | Categorizes entries under business functions: <br>• **Cost of Services** – Direct costs tied to service delivery.<br>• **Sales & Marketing Expenses** – Costs related to advertising, campaigns, and sales teams.<br>• **General & Admin Expenses** – Overhead and back-office costs. |
| **FS Group** | Financial Statement group that links entries to reporting structures (e.g., Profit & Loss, Balance Sheet). |
| **JE Source** | Source system or module from which the journal entry originated, such as AP (Accounts Payable) or AR (Accounts Receivable). |
| **JE Category** | Classifies the journal entry as **Expense**, **Revenue**, or other accounting categories. Helps in analyzing trends by category. |
| **Account** | Account number or name related to the journal entry. Used to track which accounts are frequently affected by anomalies. |
| **DimRisks** | Shows the **risk value** of the entry: High, Medium, or Low. Helps prioritize reviews. |
| **ID** | Unique system-generated identifier for each journal entry. Useful for tracing and referencing records. |
| **GL Code** | General Ledger code used for accounting and reporting. It maps the entry to the right ledger account. |
| **Entry Date** | Date when the journal entry was recorded into the system. |
| **Effective Date** | Date when the transaction becomes valid from an accounting standpoint. Often used in accrual accounting. |
| **Posting Date** | Date when the entry is posted to the General Ledger and included in financial statements. |
| **Batch Name** | Identifier of the batch that contains the journal entry. Groups related entries for processing. |
| **Batch Description** | Textual description of the batch to provide context on its purpose or contents. |
| **JE Header** | Numeric reference that groups lines of a journal entry. Acts as a high-level identifier for a journal entry block. |
| **Journal Name** | Full title of the journal or ledger book where the entry is stored (e.g., “Vendor Invoices – March”). |
| **JE Description** | Short text describing the purpose or context of the journal entry. Helps reviewers understand the reason for the transaction. |
| **Line Number** | Line index in a multi-line journal entry. Important for entries with multiple accounts affected. |
| **Debit** | The amount being **debited** (increased in assets/expenses or decreased in liabilities/equity). |
| **Credit** | The amount being **credited** (increased in liabilities/equity or decreased in assets). |
| **Anomaly Reason** | Reason given by the AI model explaining why this entry was flagged (e.g., value outlier, unusual account combination). |
|Response Correction** | Displays “Yes” if the entry is flagged by the AI model. Admin users can set this to “No” if the entry is considered valid. This feedback helps the model improve. |
| **Response Correction** | Admin-only field that allows selecting the correct reason for the anomaly from a dropdown list. Used for model training and validation. |


??? question "What's the difference between 'Value Rank' and 'Risk Rank'?"
    - **Value Rank**: Indicates how unusual a value in a journal entry (JE) is compared to typical values. For example, if the usual value is 1,000 but this time it is 10,000, the Value Rank highlights this anomaly (e.g., high, medium, low).
    - **Risk Rank**: Represents the AI model's assessment of risk, combining multiple factors such as Value Rank, Source Rank, and Category Rank. Anomalies are flagged and displayed on the dashboard based on this ranking.

!!! info "Only admin users can edit the values of **Is Anomaly** and **Response Correction**"  
    Regular users can view these fields but cannot make changes. This restriction helps ensure data integrity and proper model feedback.

---

