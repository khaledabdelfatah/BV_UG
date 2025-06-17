# **Executive Summary**

## **Overview**

The **Executive Summary** tab provides a comprehensive dashboard view designed for senior management and executives. This interface presents financial performance data across multiple analysis perspectives including Year-over-Year (YoY) comparisons, budget variance analysis, and actual performance metrics in an easy-to-interpret format.

!!! example "Executive Summary Tab"
    <iframe frameborder="0" style="width:100%;height:642px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Executive%20Summary.drawio&page-id=MKXgDpm6BVsOzMuffAAf&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1SiK-Kzx1vjFIqkBYK8SMeton-OCDQWfS%26export%3Ddownload"></iframe>

---

## **Dashboard Filters**

| **Filter** | **Function** |
|-------------|--------------|
| **Ratio Item Version** | Select between Adjusted or Standard calculations |
| **PRA** | Filter by Profit and Risk Analysis categories |
| **Ratio Calculated HFM** | Choose from predefined ratio item subsets |
| **Year** | Select annual reporting period |
| **Quarter** | Filter by specific quarters |

### **Ratio Calculated HFM Subset Management**

The **Ratio Calculated HFM** filter allows users to select from predefined subsets of ratio items. Each subset contains multiple ratio items grouped together for specific analysis purposes.

**Subset Features:**

- **Predefined Groups**: Ready-made combinations of ratio items
- **Custom Editing**: Users can modify existing subsets
- **Personal Subsets**: Each user can create and edit their own subsets
- **Flexible Selection**: Add or remove ratio items as needed

!!! example "Edit Set Dialog"
    <iframe frameborder="0" style="width:100%;height:624px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Executive%20Summary.drawio&page-id=NBYGDverXZlt1wbGPCkp&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1SiK-Kzx1vjFIqkBYK8SMeton-OCDQWfS%26export%3Ddownload"></iframe>

### **Edit Set Dialog Components**

#### **Available Members Section**

Lists all ratio items that can be added to the current subset:

- **Search Functionality**: Find specific ratio items quickly
- **Category Filters**: Filter by ratio types.
- **Selection Options**: Multiple ratio items can be selected

#### **Current Set Section**

Shows ratio items currently included in the active subset:

- **External vs Non-core**: Categorized grouping of ratio items
- **Remove Function**: Remove unwanted items from the subset
- **Real-time Preview**: See changes as they are made

#### **Available Ratio Items**

The dialog displays various ratio categories:

| **Category** | **Examples** |
|--------------|--------------|
| **Revenue Items** | Non-core Revenue, External Revenue |
| **EBITDA Items** | Non-core EBITDA, External EBITDA |
| **All Ratios** | Complete list of available ratio calculations |

### **Subset Editing Process**

1. **Access Edit Dialog**: Click the edit icon next to Ratio Calculated HFM filter
2. **Review Current Set**: Check currently included ratio items
3. **Add New Items**: Select from available members and move to current set
4. **Remove Items**: Remove unwanted items from current set
5. **Apply Changes**: Use "Apply and close" for temporary changes
6. **Save Permanently**: Click "Save" button to persist changes

### **Moving Items Between Available and Current Sets**

To move items between the Available Members and Current Set sections:

1. **Select Item(s)**: Click on the desired item(s) in the available members section.
2. **Use Move Buttons**: Click the appropriate button to move the item(s):
    - **Right Arrow (1)**: Move selected items from Available Members to Current Set.
    - **Reset Arrow (2)**: Delete all items from the current set and move only the selected items from Available Members to Current Set.

    !!! example "Move Buttons"
        <iframe frameborder="0" style="width:100%;height:624px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Executive%20Summary.drawio&page-id=NBYGDverXZlt1wbGPCkp&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1SiK-Kzx1vjFIqkBYK8SMeton-OCDQWfS%26export%3Ddownload"></iframe>

### **Save Options**

| **#** | **Button Name**      | **Description and Result**                                                                                                                                                                                                                      |
|-------|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1**   | Replace and Close    | Restores the subset to its original default configuration, discarding all current changes, and closes the dialog.                                                                                                                                |
| **2**   | Save                 | Saves all changes permanently to the database. When clicked, a dialog appears allowing you to enter a name for the subset. You can also choose to make the set public (visible to all users) by checking the "Show Public" option, or keep it private (visible only to you) by leaving it unchecked. |
| **3**   | Apply and Close      | Applies the current changes for this session only (temporary), and closes the dialog. These changes will be lost when the session ends unless you save them.                                                                                    |
| **4**   | Close                | Closes the dialog without saving or applying any changes made during the current session.                                                                                                                 |

!!! example "Save Options"
    <iframe frameborder="0" style="width:100%;height:702px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Executive%20Summary.drawio&page-id=r9VxPaqyafdtPJeqXlpc&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1SiK-Kzx1vjFIqkBYK8SMeton-OCDQWfS%26export%3Ddownload"></iframe>

!!! warning "Important Save Notice"
    Changes made with "Apply and close" are temporary and will be lost when the session ends. Always click "Save" to make permanent changes that will persist across sessions.

---

## **Dashboard Sections**

### **Year-over-Year (YoY) Analysis**

The YoY section compares current performance against the same period in the previous year.


**Performance Metrics:**

- **Revenue**: Primary revenue indicators with percentage changes
- **EBITDA**: Earnings before interest, taxes, depreciation, and amortization

**Color Coding:**

- **Green**: Positive growth performance
- **Red**: Declining performance
- **Orange/Yellow**: Moderate performance changes

### **Budget Variance (vs Budget)**

This section shows actual performance compared to budgeted targets.

**Analysis Framework:**

- **Variance Calculation**: Actual minus budgeted amounts
- **Percentage Variance**: Relative performance against budget
- **Entity-Level Analysis**: Individual subsidiary budget performance

**Color Indicators:**

- **Green**: Performance exceeding budget
- **Red**: Performance below budget expectations
- **Orange**: Mixed or marginal performance

### **Actual Performance**

The Actual section displays absolute performance figures without comparison metrics.

**Data Presentation:**

- **Revenue Figures**: Actual revenue amounts by entity
- **EBITDA Values**: Operational profitability indicators
- **Subsidiary Breakdown**: Individual entity contributions

---

 