
# **File Tracking Panel**

The File Tracking Panel is a centralized dashboard designed to monitor and validate the latest data uploads for financial reporting. It allows users and administrators to track the most recent activity related to three core file types:

- General External Files
- Budget Files
- Forecast Files

Each file type corresponds to a tab in the system's backend, with uploads reflected in near real-time.

The panel ensures transparency and traceability for all data loads into the system by showing timestamps, inserted row counts, and the user responsible for each upload.

## **File Source Paths**

Each button on the dashboard (General, Budget, Forecast) retrieves the last uploaded files from a specific folder path configured on the backend. These paths are predefined and shared by the team. The panel does not allow file uploads directly, but rather reflects what has already been dropped in these backend folders.

---

## **Panel Overview**

The interface is divided into three main views, each accessible via buttons at the top right:

- **General**
- **Budget**
- **Forecast**

Each view displays the **last 10 updates** related to its corresponding file type, including important details like timestamps, inserted rows, and the user who performed the action.

---

## **Components and Layout**

Each data view (General, Budget, Forecast) includes a data table with the following columns:

| **Column Name**       | **Description**                                                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------- |
| **Start Date / Time** | The timestamp when the upload process began.                                                        |
| **End Date / Time**   | The timestamp when the upload process was completed.                                                |
| **Inserted Rows**     | The number of rows successfully inserted into the system.                                           |
| **User**              | The system user or administrator who performed the upload.                                          |
| **Last Updated ID**   | A unique system-generated identifier for the upload instance. |

---

## **How to Use the Panel**

1. **Navigate to the appropriate view**:

    - Click **General** to retrieve General External File from the designated path.
    - Click **Budget** to retrieve Budget File from the designated path.
    - Click **Forecast** to retrieve Forecast File from the designated path.

2. **Review the upload logs**:
    - Check the **date/time** to verify when the last update occurred.
    - Look at the **Inserted Rows** to confirm if the file was populated and processed correctly.
    - Use the **User** column to trace responsibility for the upload.
    - Track by **Last Updated ID** in case you need to escalate an issue or reference logs.

---

## **Templates Reference**

When uploading files, ensure they adhere to the following templates for each file type. These templates define the required columns and data formats to ensure successful integration into the system.

### **General External File Template**

| Column                    | Description                                | Example               |
| ------------------------- | ------------------------------------------ | --------------------- |
| `entity_code`             | Business unit code (must match system).    | `STC_BHR`, `CHANNELS` |
| `measure_type`            | Financial metric type.                     | `Revenue`, `EBITDA`   |
| `value_type`              | Type of value (Actual, Budget, Forecast).  | `Actual`              |
| `KPI_type`                | KPI category.                              | `Non-Core`, `EBITDA`  |
| `month`                   | Reporting period: `3m`, `6m`, `9m`, `12m`. | `3m`                  |
| `year`                    | 4-digit year.                              | `2024`                |
| `sub_type`                | Sub-category of financial data.            | `Mobile`, `Fixed`     |
| `sub_type2` – `sub_type9` | Optional further classifications.          | *(Optional)*          |
| `value`                   | The numeric value to upload.               | `1500000`             |

### **Budget File Template**

| Column         | Description                 | Example         |
| -------------- | --------------------------- | --------------- |
| `period`       | 3-letter month abbreviation | `Jan`, `Feb`    |
| `year`         | 4-digit year                | `2024`          |
| `entity_code`  | Business unit code          | `202000`        |
| `account_code` | Financial account affected  | *(System code)* |
| `value_SAR`    | Budgeted value in SAR       | `1500000`       |

### **Forecast File Template**

| Column          | Description                | Example         |
| --------------- | -------------------------- | --------------- |
| `year`          | 4-digit year               | `2024`          |
| `as_of_quarter` | Quarter abbreviation       | `Q1`, `Q2`      |
| `account_code`  | Financial account affected | *(System code)* |
| `entity_code`   | Business unit code         | `101000`        |
| `value_SAR`     | Forecasted value in SAR    | `1500000`       |
