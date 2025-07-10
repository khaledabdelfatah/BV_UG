# **Group Ratio Item**

## **Overview**

The **Group Ratio Item** tab enables users to define and manage ratio items for correlation, profitability, and performance analysis across group entities and regions (such as KSA and subsidiaries). Key actions include:

- Creating new ratio items
- Updating existing entries
- Setting and adjusting reporting periods

!!! example "Ratio Item Tab"
    <iframe frameborder="0" style="width:100%;height:491px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Ratio%20Item.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ViQwJ7Ct2HkwjA43M8LpeCm888kdrd0S%26export%3Ddownload"></iframe>

This tab supports robust data governance by linking ratio logic to structured source systems (e.g., HFM, external files).

---

## **View Options**

You can customize the visible columns using the "User Input Ratio HFM Selection" dropdown at the top of the tab. This allows you to focus on relevant data for your current task:

!!! example "View Options"
    <iframe frameborder="0" style="width:100%;height:683px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Ratio%20Item.drawio&page-id=Y3O3BH7MlOs8ioVthGBp&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ViQwJ7Ct2HkwjA43M8LpeCm888kdrd0S%26export%3Ddownload"></iframe>

| **View**          | **Purpose / Shown Columns**                                                                                                                                                                                     |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Default**       | Displays all available columns.                                                                                                                                                                                 |
| **External File** | Shows columns sourced from external files:<br> `Ratio Item`, `KPI Type`, `Measure Type`, `Subtype`, `Period Type`, `Negate`, `Exclude`, `Subsidiary`, `Balance Type`                                            |
| **Profitability** | Highlights PL-related columns:<br> `Ratio Item`, `PL1`, `PL2`, `PL3`, `BU`                                                                                                                                      |
| **Group and KSA** | Focuses on Group and KSA metadata:<br> `Ratio Item`, `Numeric`, `Period Type`, `Min`, `Max`, `Negate`, `Exclude`, `KSA Ratio Item`, `Group Account`, `Subsidiary`, `Subsidiary Account`, `Balance Type`          |

---

## **Table Columns**

| **Column**             | **Description**                                                                                                                                                                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Serial Number**      | Unique identifier for each ratio item.                                                                                                                                                                                                           |
| **Ratio Item**         | Name of the ratio being defined or calculated.                                                                                                                                                                                                   |
| **KPI Type**           | Category of Key Performance Indicator.                                                                                                                                                                                                           |
| **Measure Type**       | Specifies the measurement logic (e.g., ratio, value).                                                                                                                                                                                            |
| **Subtype**            | Further classification, often sourced from external files.                                                                                                                                                                                       |
| **Numeric**            | Indicates if the item contains numeric data.                                                                                                                                                                                                     |
| **Period Type**        | Reporting frequency:<br>• **Periodic**: Regular intervals (default for KSA source)<br>• **QTD**: Quarter to Date<br>• **YTD**: Year to Date (default for HFM source)                                                                             |
| **Min / Max**          | Thresholds for filtering or validating the item’s value.                                                                                                                                                                                         |
| **Negate**             | If "Yes", the value is mathematically negated (multiplied by -1).                                                                                                                                                                               |
| **Exclude**            | If "Yes", the item is excluded from ratio calculations.                                                                                                                                                                                          |
| **KSA Ratio Item**     | Reference to a KSA-specific ratio line item from their dashboard.                                                                                                                                                                                |
| **Group Account**      | Financial account used at the group consolidation level.                                                                                                                                                                                         |
| **Subsidiary**         | Name or code of the local entity or subsidiary.                                                                                                                                                                                                  |
| **Subsidiary Account** | Specific account code used by the subsidiary.                                                                                                                                                                                                    |
| **Balance Type**       | Specifies the type of value reported for the ratio item:<br><br>• **Balance**: Value at the end of the reporting period, representing a point-in-time snapshot.<br>• **Opening Balance**: Value at the start of the reporting period, useful for tracking changes from period start.<br>• **Average Balance**: Mean value calculated over the reporting period, smoothing fluctuations.<br>• **Annualized Balance**: Value projected to represent a full year, enabling comparability across periods.<br>• **Balance PY**: Value from the same period in the previous year, supporting year-over-year analysis.<br>• **Balance PP**: Value from the immediately preceding period, enabling period-over-period comparisons. |
| **PL1 / PL2 / PL3**    | Business Line defined by the profitability team                                                                                                                                                                                  |
| **BU**                 | Business Unit (e.g., **CBU**, **NMU**, etc.)                                                                                                                                                                                                     |

---

## **How to Use the Tab**

### Creating a New Ratio Item

1. Scroll to the last row of the table.
2. Enter the required values in the relevant columns.
3. Click **Create** (top-right) to save the new entry.

### Updating Existing Items

1. Locate the row(s) you want to update.
2. Edit the fields directly.
3. Click **Update All** (top-right) to apply your changes.

> **Tip:** You can update multiple rows in one action.

### Updating the Reporting Period

1. Click **Update Period** (top-right).
2. In the popup, insert the **Year** and **Month**.
3. Click **OK** to apply changes.

> **Note:** When you update the period, existing data is kept. This lets you track time series data across months or years.

---

### **Best Practices**

- Use the **Exclude** option with caution. If you select "Yes," the item will be removed from dashboards and calculations.
- Set **Min** and **Max** thresholds to enforce data validation and prevent incorrect values.
- Follow naming conventions. For example, start PL-related ratio names with `PR-` to make them easy to identify.
- Make sure the **Group Account** and **Subsidiary Account** fields are consistent. Inconsistencies can cause reporting errors.
