# **Ratio External**

## **External File Template**

Below is a detailed description of each column required in the external data file. Use this table as a reference to ensure correct formatting and data consistency.

| **Column Name** | **Description** | **Example / Notes** |
|-----------------|----------------|---------------------|
| `entity_code`   | Unique code for the subsidiary or business unit. Must match the code used in the system. | `STC_BHR`, `CHANNELS` |
| `measure_type`  | Type of financial measure being analyzed. | `Revenue`, `EBITDA`, `WAC` |
| `value_type`    | Perspective of the value. | `Actual`, `Budget`, `Forecast` |
| `KPI_type`      | Key performance indicator category. | `Non-Core`, `Device`, `EBITDA` |
| `month`         | Reporting period. Use `3m` (Q1), `6m` (H1), `9m` (Q3), `12m` (Full Year). | `3m`, `6m`, `9m`, `12m` |
| `year`          | Year of the financial data. | `2023`, `2024` |
| `sub_type`      | Specific subtype of the financial measure. | e.g., `Mobile`, `Fixed` |
| `sub_type2`     | Second-level subtype (optional). | Leave empty if not applicable |
| `sub_type3`     | Third-level subtype (optional). | Leave empty if not applicable |
| `sub_type4`     | Fourth-level subtype (optional). | Leave empty if not applicable |
| `sub_type5`     | Fifth-level subtype (optional). | Leave empty if not applicable |
| `sub_type6`     | Sixth-level subtype (optional). | Leave empty if not applicable |
| `sub_type7`     | Seventh-level subtype (optional). | Leave empty if not applicable |
| `sub_type8`     | Eighth-level subtype (optional). | Leave empty if not applicable |
| `sub_type9`     | Ninth-level subtype (optional). | Leave empty if not applicable |
| `value`         | Actual value of the financial measure. | Numeric value, e.g., `1500000` |

**Notes:**
- All subtype columns (`sub_type2` to `sub_type9`) are optional and can be left empty if not required for your analysis.
- Ensure all codes and values are consistent with those used in the system for accurate data integration.

