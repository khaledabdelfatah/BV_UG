# **Ratio External**

The Ratio External tab enables you to view financial ratios calculated from external data sources, supporting the integration of financial measures from subsidiaries or business units for comprehensive, cross-entity analysis. The dashboard presents this external financial data through interactive tiles that offer clear visualization and robust analysis capabilities.

## **How Data is Loaded**

Data is loaded into the Ratio External dashboard through a structured process that ensures accuracy and consistency. The system pulls data from designated external excel files, which must adhere to specific templates for proper integration. The data is then processed and displayed in various tiles for easy analysis.

### **External File Template**

Below is a table describing each column required in the external data file. Use this as a reference for correct formatting and data consistency.

| **Column Name** | **Description** | **Example / Notes** |
|-----------------|----------------|---------------------|
| `entity_code`   | Unique code for the subsidiary or business unit. Must match the code used in the system. | `STC_BHR`, `CHANNELS` |
| `measure_type`  | Type of financial measure being analyzed. | `Revenue`, `EBITDA`, `WAC` |
| `value_type`    | Perspective of the value. | `Actual`, `Budget`, `Forecast` |
| `KPI_type`      | Key performance indicator category. | `Non-Core`, `Device`, `EBITDA` |
| `month`         | Reporting period. Use `3m` (Q1), `6m` (H1), `9m` (Q3), `12m` (Full Year). | `3m`, `6m`, `9m`, `12m` |
| `year`          | Year of the financial data. | `2023`, `2024` |
| `sub_type`      | Specific subtype of the financial measure. | e.g., `Mobile`, `Fixed` |
| `sub_type2` - `sub_type9` | Additional subtypes (optional). Leave empty if not applicable. |  |
| `value`         | Actual value of the financial measure. | Numeric value, e.g., `1500000` |

!!! info "Important Notes"
    - All subtype columns (`sub_type2` to `sub_type9`) are optional and can be left empty if not required for your analysis.
    - Ensure all codes and values are consistent with those used in the system for accurate data integration.

### **Budget Template**

| **Column Name** | **Description** | **Example / Notes** |
|-----------------|----------------|---------------------|
| `period`        | Budget period (3-char month abbreviation) | `Jan`, `Feb`, `Mar`, etc. |
| `year`          | Year for which the budget is applicable | `2023`, `2024` |
| `entity_code`   | Unique code for the subsidiary or business unit | `202000`, `101000` |
| `account_code`  | Code for the financial account or measure |  |
| `value_SAR`     | Budgeted value in Saudi Riyals (SAR) | Numeric value, e.g., `1500000` |


## **Dashboard Filters**

| **Filter** | **Function** |
|-------------|--------------|
| **KPI Type** | Select performance indicator categories (Non-Core, Revenue, EBITDA) |
| **Measure Type** | Choose financial measures (Revenue, Cost, Profit) |
| **Value Type** | Select data perspective (Actual, Budget, Forecast) |
| **Year** | Define annual reporting period |
| **Month** | Select quarterly periods (Q1, Q2, Q3, Q4) |

---

## **Dashboard Tiles**

### **Measures by Subsidiary Tile**

This tile displays subsidiary performance in a horizontal bar chart format (sorted by performance).

### **Subtype Details Tile**

This tile breaks down performance by service categories.

### **Exploration and Consolidation Tile**

This tile provides detailed tabular data for comprehensive analysis.

### **Actual vs Budget Tile**

This tile compares actual performance against budget targets.