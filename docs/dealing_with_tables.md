# **Dealing with Tables**

Tables in the dashboard provide essential tools for data management and analysis. This section explains how to use table features to streamline your workflow and gain deeper insights.

## **Overview of Table Features**

Explore the following capabilities to maximize your use of tables:

- **Context Menu Actions**: Access quick options by right-clicking on rows or columns. Perform actions such as keeping or hiding rows, restoring hidden data, and undoing recent changes.

- **Sorting and Filtering**: Organize your data by sorting columns in ascending or descending order. Apply filters to focus on top or bottom entries, making it easier to identify trends and outliers.

- **Formatting Options**: Adjust how data appears by selecting from various formats, including general, currency, percentage, and custom formats. Consistent formatting improves readability and clarity.

- **Conditional Formatting**: Highlight important values based on specific criteria. Use color and style changes to emphasize data that meets defined conditions.

- **Drill-Down and Drill-Through**: Investigate details behind summary figures. Drill down to view granular data or drill through to related reports for comprehensive analysis.

Use these features to efficiently manage, visualize, and analyze data within dashboard tables.

!!! example "Table Features Overview"
    <iframe frameborder="0" style="width:100%;height:722px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Dealing%20with%20Tables.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D18gn9ckPKX6A9oGvO_Rr3ao0iJ0vJMWeD%26export%3Ddownload"></iframe>

---

## **Table Context Menu**

Right-clicking on a table row or column opens a context menu with several options:

### **Row and Column Actions**

- **Keep**: Display only the selected row for focused analysis.
- **Hide**: Temporarily remove the selected row to declutter the table.
- **Unhide All**: Restore all hidden rows to show the complete dataset.
- **Undo**: Revert the last action, such as restoring a recently hidden row.

!!! tip "Quickly Restore Hidden Rows"
    Use the undo button to bring back the last hidden row, or select 'Unhide All' to restore all hidden rows.

### **Sorting Options**

- **Sort Ascending**: Arrange rows in ascending order based on the selected column (e.g., lowest values or earliest dates).
- **Sort Descending**: Arrange rows in descending order (e.g., highest values or latest dates).
- **Clear Sort**: Remove all sorting and return to the original order.
- **Sort Hierarchy**: Sort by multiple columns in a prioritized manner for advanced ordering.

### **Filtering and Formatting**

- **Top/Bottom Filter**: Show only the top or bottom entries based on a column (e.g., top 10 or bottom 5).
- **Format Value**: Change the display format of values in the selected column for improved readability.

---

## **Formatting Options**

Apply various formats to your data for clarity and consistency:

| **Format**                | **Description**                                                        | **Example**         |
|---------------------------|------------------------------------------------------------------------|---------------------|
| General                   | Default format without styling.                                        | `12345.67`          |
| Fixed                     | Number with two decimal places.                                        | `12345.67`          |
| Comma                     | Adds thousands separator.                                              | `12,345.67`         |
| Rounded                   | Rounds to the nearest whole number.                                    | `12,346`            |
| Percentage                | Converts number to a percentage.                                       | `12,345.67%`        |
| Scientific                | Scientific notation format.                                            | `1.234567E+4`       |
| Accounting                | Currency with accounting alignment.                                    | `$12,345.67`        |
| Currency                  | Standard currency format.                                              | `$12,345.67`        |
| Currency (Rounded)        | Currency rounded to whole numbers.                                     | `$12,346.00`        |
| Thousands (K)             | Shortens numbers in thousands.                                         | `12.3K`             |
| Millions (M)              | Shortens numbers in millions.                                          | `12.3M`             |
| Short Abbreviation        | Auto-shortens numbers using K/M/B.                                     | `12.3K`             |
| Date                      | Formats as date.                                                       | `4/28/25`           |
| Time                      | Formats as time.                                                       | `4:04:00 PM`        |
| Custom Format             | Enter your own format code in the popup and click Apply.               | Custom input        |
| Negative with Minus Sign  | Shows negative values with a minus sign.                               | `-12345.67`         |
| Use Database Format       | Retains the original database format.                                  |                     |

---

## **Conditional Formatting**

Highlight values in a column based on specific criteria (e.g., values above a threshold or within a range). For each condition, you can specify formatting styles such as text color to emphasize important data.

---

## **Drill Options**

Explore related data directly from the table:

- **Drill Down**: Click a row to view more detailed information, such as transactions or components of a larger figure. Useful for financial data analysis.
- **Drill Up**: Return to the summary view after drilling down to see the broader context.
- **Drill Through**: Access detailed reports or related datasets directly from the table for deeper analysis.

    - **Balance Drill Through**: View journal entries that make up the balance for an account. Analyze anomalies, GL code entries, effective dates, credits, debits, and other details.
    - **Journal Entries Drill Through**: View sub-ledger details, including transaction dates, amounts, and descriptions. Note: Loading large datasets may take additional time.
    - **Balance Previous Period Drill Through**: View journal entries for an account in the previous period to gain historical insights.
    - **Variance Previous Period Drill Through**: Identify root causes of variances in the previous period, including account analysis and impact percentages.
    - **Current Balance Drill Through**: View FAH Data for the current balance of an account.

!!! tip "Root Cause Analysis via Drill Through"
    To identify the root cause for an account, select the desired account in the table, right-click on the "Variance Previous Period" column, and choose **Drill Through > Root Cause**.  
    For non-account fields, right-click on the "% of Change Previous Period" column and select **Drill Through > Root Cause** to analyze the underlying factors driving the change.

## **Conclusion**

Tables are powerful tools for data analysis and management within the dashboard. By utilizing the context menu, formatting options, conditional formatting, and drill features, you can effectively interact with your data, uncover insights, and make informed decisions. Familiarize yourself with these features to enhance your dashboard experience and streamline your workflow.