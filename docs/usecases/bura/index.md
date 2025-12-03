# **Business Units Revenue Analysis (BURA)**

## **Overview**

The Business Units Revenue Analysis (BURA) solution provides BU Analysts with an automated, governed Planning Analytics Workspace (PAW) environment for consolidated revenue analysis and reporting.

!!! info "Key Information"
    This guide helps you navigate the BURA workspace, interpret reports, and manage data updates effectively.

---

## **Understanding the Analysis Framework**

The BURA solution organizes analysis across **five output tabs**, each serving a specific purpose in the revenue analysis workflow.

### **Core Metrics**

All reports use **Net Movement** as the primary metric, measured in two time frames:

- **PTD** (Period-to-Date): Current month performance
- **YTD** (Year-to-Date): Cumulative annual performance

These metrics can be compared against three scenarios:

| Scenario | Description |
|----------|-------------|
| **Actual** | Current period results |
| **Budget** | Planned targets |
| **Prior Year** | Historical comparison |

---

## **Analysis and Output Tabs**

### **High-Level Diagnostics**

These tabs provide executive summaries and visual diagnostics for quick performance assessment.


#### **Overview Tab**

**Purpose:** Executive Summary Dashboard

The Overview tab delivers a high-level performance snapshot across the entire organization, designed for quick visual diagnostics and executive review.

!!! question "Key Question"
    How are we performing overall, and where are the biggest deviations?

**What You'll Find:**

- **Total Revenue Bridge Visuals**: Visual breakdowns showing Year-over-Year (YoY) and Actual vs. Budget variances
- **BU Comparisons**: Performance across CBU, EBU, and WBU business units
- **Variance Highlights**: Immediate identification of positive and negative trends

!!! tip "Recommended Workflow"
    1. Start with the Overview tab to identify the largest variances
    2. Note which BU shows significant deviation
    3. Navigate to the corresponding Breakdown tab for detailed investigation



!!! example "Overview Tab Interface"
    <iframe frameborder="0" style="width:100%;height:356px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=G9-8PxkmytD6iclVAYSU&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

#### **Revenue Performance Tab**

**Purpose:** Growth Rate and Driver Analysis

This tab focuses on operational metrics and growth indicators that influence revenue generation.

!!! question "Key Question"
    How fast are we growing, and which operational metrics are driving the results?

**What You'll Find:**

- **Growth Percentages**: Rate of change metrics across periods
- **Operational KPIs**: Customer count, Average Revenue Per User (ARPU), and other business drivers
- **Trend Analysis**: Time-series views of key performance indicators

!!! note "Usage"
    Monitor the health of underlying business drivers that generate the revenue numbers shown in the Overview tab.

!!! example "Revenue Performance Tab Interface"
    <iframe frameborder="0" style="width:100%;height:352px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=_O2P2Pqt75jv2wy1IEmx&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

### **Detailed Analysis and Breakdown Tabs**

The CBU, EBU, and WBU Breakdown tabs provide granular detail for deep-dive analysis of specific business units.

**Purpose:** Regional and organizational revenue analysis

**What You'll Find:**

- **Detailed Data Grids**: Net Movement (PTD/YTD) broken down by:
    - Account
    - Product
    - Customer dimensions
- **Multi-dimensional Analysis**: Cross-tabulated views for comprehensive insight
- **Drill-down Capability**: Navigate from summary to transaction-level detail

!!! tip "Analysis Approach"
    Use these tabs after identifying variances in the Overview tab to understand the root causes at the account, product, or customer level.

!!! example "Breakdown Tabs Interface"
    <iframe frameborder="0" style="width:100%;height:357px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=bbjyH1ItKer6Etqm9781&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

### **Critical Metrics Reference**

When reviewing detailed grids, focus on these financial metrics:

| Metric | Time Period | Description |
|--------|-------------|-------------|
| **Net Movement (PTD)** | Period-to-Date | Current month net revenue movement |
| **Net Movement (QTD)** | Quarter-to-Date | Quarterly net revenue movement |
| **Net Movement (YTD)** | Year-to-Date | Annual cumulative net revenue movement |

---

## **Data Management and Mapping**ng**

### **The Mapping Tab**

The Mapping tab serves as the data governance and loading control center for the BURA solution.

#### **Mapping Grid (Data Classification)**

**Purpose:** Establish rules for revenue data categorization

The Mapping Grid allows you to define how source system data elements are classified within Planning Analytics.

!!! info "Mapping Process"
    You map source data elements (Accounts, Products) to Planning Analytics categories (Revenue Type, Revenue Stream) to ensure accurate data grouping and filtering across all reports.

**Key Activities:**

- Define classification rules
- Map source accounts to revenue categories
- Assign products to revenue streams
- Maintain data governance standards

---

#### **Data Update Controls**

Two action buttons at the top-right of the Mapping tab trigger official data loading processes.

| Button | Action | Data Source | Description |
|--------|--------|-------------|-------------|
| **Update Actual** | Load actual revenue data | ERP System | Updates all reports with current period actuals |
| **Update Budget** | Load budget data | CSV file (shared folder) | Updates all reports with planned targets |

!!! warning "Important"
    Only authorized analysts should trigger data updates. These processes refresh data across all reports and may take several minutes to complete.

!!! tip "Best Practice"
    - Verify the data source is current before triggering updates
    - Run updates during off-peak hours to minimize user impact
    - Validate mapping rules before loading new data


!!! example "Mapping Tab Interface"
    <iframe frameborder="0" style="width:100%;height:355px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Data%20Source%20Audit%20%26%20Utilization%20Monitoring.drawio&page-id=rWGQddOfZAa77dtVOaaB&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1KlLLWMHqG3BrhF_6xIusE8Lur6lBaTb5%26export%3Ddownload"></iframe>

---

## **Recommended Analysis Workflow**

Follow this workflow to maximize the effectiveness of BURA:

1. **Start with Overview Tab**
    - Review the Total Revenue Bridge
    - Identify significant variances (YoY and Actual vs. Budget)
    - Note which BU(s) require investigation

2. **Check Revenue Performance Tab**
    - Assess growth rates and trends
    - Verify operational KPIs align with revenue performance
    - Identify any concerning driver metrics

3. **Deep Dive in Breakdown Tabs**
    - Navigate to the specific BU tab (CBU, EBU, or WBU)
    - Analyze detailed grids by Account, Product, and Customer
    - Drill down to transaction level if needed

4. **Maintain Data Governance**
    - Review and update mapping rules as needed
    - Trigger data updates according to schedule
    - Validate data accuracy after updates
