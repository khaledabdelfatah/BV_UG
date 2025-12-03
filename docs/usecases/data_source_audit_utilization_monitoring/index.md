# **Data Source Audit & Utilization Monitoring**

## **Overview**

This guide provides Business Administration and Auditing Teams with near real-time visibility into data readiness and system utilization across the IBM Planning Analytics environment.

!!! info "Target Audience"
    Business Administration and Auditing Teams responsible for data governance, system monitoring, and compliance tracking.

---

## **Key Capabilities**

The monitoring system delivers two critical capabilities for operational excellence:

### **Data Readiness Visibility**

Monitor the execution status of all TurboIntegrator (TI) processes that load data into financial dashboards.

**Benefits:**

- Verify data integrity in real-time
- Ensure reports use the latest successfully loaded data
- Validate data readiness before management reviews
- Support confident decision-making with current data

### **User Adoption and Activity Audit**

Gain comprehensive insights into system utilization and user engagement patterns.

**Benefits:**

- Track system adoption rates across teams
- Monitor specific user behavior patterns
- Confirm compliance with usage policies
- Identify training needs and optimization opportunities

!!! tip "Best Practice"
    Review both monitoring tabs daily to ensure data integrity and track system adoption trends.

---

## **Process Tracking Tab**

**Purpose:** Monitor TurboIntegrator (TI) process execution and data loading status

The Process Tracking tab enables Operations and Admin teams to monitor the successful loading of financial data and identify issues before they impact reporting.

!!! example "Process Tracking Tab Interface"
    <iframe frameborder="0" style="width:100%;height:451px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=pepVIVfoydO_NYxVbntX&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

### **Quick Status Check**

#### **Processes by Status (Donut Chart)**

This visualization provides an immediate snapshot of process execution health.

!!! warning "Status Indicators"
    A high number of **Failed** (Red) processes indicates potential data readiness issues requiring immediate attention.

**How to Use:**

1. Review the donut chart for the overall process health distribution
2. Focus on the failed process count (red segment)
3. Use the percentage to assess the severity of issues

#### **TI Status Filter**

Quickly isolate processes by their execution status for focused analysis.

!!! tip "Quick Filtering"
    Use the TI Status filter to display only **Failed** processes for immediate investigation and remediation.

---

### **Process Execution Details**

The detailed table provides a comprehensive audit log of every process execution with the following key columns:

| Column | Purpose | Details |
|--------|---------|---------|
| **Process Name** | Identification | The name of the TI process that executed |
| **Status** | Data Readiness Indicator | Success, Failed, or Running status |
| **Error Message** | Troubleshooting | Technical details when Status is Failed (mandatory field) |
| **User** | Accountability | TM1 user who executed the process |
| **Duration** | Performance | Total execution time in seconds or minutes |
| **Start Timestamp** | Tracking | Exact date and time when process began |
| **End Timestamp** | Tracking | Exact date and time when process completed |

!!! note "Audit Trail"
    This table serves as the official audit log for all data loading activities in the Planning Analytics environment.

---

### **Troubleshooting Failed Processes**

When a process shows a **Failed** status, follow this systematic approach:

!!! danger "Critical: Failed Process Procedure"
    **Step 1: Review Error Details**
    
    - Locate the process in the table
    - Read the **Error Message** column carefully
    - Identify the failure type (e.g., file not found, data type mismatch, connection timeout)
    
    **Step 2: Escalate to IT Team**
    
    - Provide the **Process Name**
    - Include the complete **Error Message**
    - Note the **Start/End Timestamp** for context
    - Specify any patterns (e.g., recurring failures)

#### **Common Error Types**

| Error Type | Likely Cause | Typical Resolution |
|------------|--------------|-------------------|
| File not found | Source file missing or path incorrect | Verify file location and permissions |
| Data type mismatch | Data format doesn't match expected type | Check source data format |
| Connection timeout | Network or server connectivity issue | Verify server status and network |
| Memory error | Large dataset or insufficient resources | Review process optimization or server capacity |

---

## **Utilization Report Tab**

**Purpose:** Monitor user activity, system adoption, and engagement patterns

The Utilization Report tab enables Administration and Auditing teams to track system usage, identify adoption trends, and audit specific user behaviors.

!!! example "Utilization Report Tab Interface"
    <iframe frameborder="0" style="width:100%;height:369px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=_Hl423HAnQd-xHgWRwPd&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

### **High-Level Visualizations**

#### **Total Users by Group**

**What It Shows:** Distribution of active users across different user groups (e.g., HFM, GL, Finance).

**Use Case:** Identify which teams are most engaged with the system and spot underutilized groups that may need additional training or support.

#### **Total Users by Use Case**

**What It Shows:** Number of users accessing each functional area or use case.

**Use Case:** Understand which Planning Analytics features are most heavily adopted and which may require promotion or training.

#### **Use Case Adoption Breakdown**

**What It Shows:** Comparative view of engagement across different use cases (e.g., Group Ratio Analysis, Anomaly Detection, Variance Analysis).

**Use Case:**

- Identify the most utilized functionalities
- Spot underutilized features that may need promotion
- Justify investment in specific modules based on adoption

#### **Monthly Activity Trend**

**What It Shows:** Time-series visualization of user activity patterns over days and months.

**Use Case:**

- Identify peak usage days for system maintenance planning
- Understand seasonal patterns in system load
- Track adoption growth over time
- Plan capacity and resource allocation

!!! tip "Analysis Insight"
    Cross-reference peak activity days with business cycles (e.g., month-end close, quarterly reviews) to optimize system performance during critical periods.

---

### **Activity Drill-Down (Audit Detail)**

The detailed activity table provides granular audit information for compliance and behavior analysis:

| Column | Audit Purpose | Usage |
|--------|---------------|-------|
| **User** | Identity tracking | Specific User ID being audited for compliance or behavior analysis |
| **User Groups** | Role-based analysis | User's assigned role or group (e.g., HFM User, Finance Analyst) |
| **Use Case** | Feature engagement | Specific functionality the user accessed or utilized |
| **Activity Type** | Interaction classification | Distinguishes between **Edit** (data modification) and **View** (read-only) actions |
| **Count** | Frequency metric | Number of times the user performed the specified action within the filtered period |

!!! info "Activity Type Definitions"
    - **Edit:** User modified data, updated values, or changed configurations
    - **View:** User accessed reports or dashboards in read-only mode

---

### **Filtering for Effective Auditing**

Use the filter controls at the top of the tab to narrow your audit scope and answer specific questions:

#### **User Groups Filter**

**Use For:**

- Focusing on a specific team (e.g., Finance, Operations)
- Comparing activity levels between departments
- Identifying underutilized groups

**Example:** Filter to "HFM User" to see all HFM team activity patterns.

#### **Use Case Filter**

**Use For:**

- Analyzing engagement with specific functionality
- Tracking adoption of newly deployed features
- Understanding which reports or dashboards are most accessed

**Example:** Filter to "Anomaly Detection" to see how many users viewed or edited anomaly reports.

#### **Time Period Filter**

**Use For:**

- Comparing activity between different periods
- Tracking adoption growth over time
- Investigating specific incidents or compliance periods

!!! tip "Audit Workflow"
    1. Start with high-level visualizations to identify trends
    2. Apply filters to narrow focus to specific teams or use cases
    3. Review the detailed activity table for granular audit information
    4. Export data if needed for compliance reporting or further analysis
