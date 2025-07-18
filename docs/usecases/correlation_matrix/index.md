# **Correlation Matrix**

The Correlation Matrix dashboard is a powerful analytical tool designed to help users uncover relationships between subsidiary accounts by visualizing how their values move together over time. By highlighting hidden dependencies, behavioral patterns, and potential anomalies, the dashboard supports data-driven decision-making across financial and operational datasets.

## **Purpose**

The Correlation Matrix provides a visual analysis of relationships between source accounts within a selected subsidiary. Users can quickly identify which accounts move in tandem, which are independent, and which behave inversely. This insight aids in understanding business processes, ensuring data consistency, and detecting financial patterns.

## **Key Features**

- **Account-to-Account Heatmap:** Visualizes correlations between source accounts using a color gradient. Darker shades indicate stronger correlations (positive or negative), while lighter shades represent weak or no correlation.
- **Hover Insight:** Hovering over any cell displays the two source accounts being compared and their correlation coefficient (ranging from -1 to +1).
- **Entity Filter:** A dropdown filter (top-right) allows users to focus on correlations within a specific CIF/subsidiary.

## **Selecting a Subsidiary**

To analyze a specific subsidiary, use the dropdown filter in the top-right corner of the dashboard. The matrix will update to display correlations only for accounts within the selected entity.

!!! example "Correlation Matrix"
    <iframe frameborder="0" style="width:100%;height:518px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Correlation%20Matrix.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1LkCCTe7vRbgLR58Dv9UhNTXtOvHhjLw1%26export%3Ddownload"></iframe>

## **How to Read the Correlation Matrix**

The matrix measures how similarly account values change over time. Each cell represents the correlation between two accounts.

### **1. Color Intensity = Strength of Correlation**

- **Darker Purple:** Strong correlation (positive or negative)
- **Lighter Purple / White:** Weak or no correlation

This visual cue allows you to quickly spot strong relationships.

### **2. Hover for Details**

Hovering over a cell reveals:
- The two source account codes being compared
- The correlation coefficient (between -1 and +1)

**Example:**
```
530209 | 120636-4
Correlation Coefficient: -0.09
```

### **3. Interpreting Correlation Coefficients**

| Coefficient      | Interpretation                | Business Meaning                                 |
|------------------|------------------------------|--------------------------------------------------|
| +1               | Perfect positive correlation  | Accounts move together exactly                   |
| +0.5 to +0.99    | Strong positive correlation   | Often increase/decrease together                 |
| 0                | No correlation                | Accounts behave independently                    |
| -0.5 to -0.99    | Strong negative correlation   | When one goes up, the other goes down            |
| -1               | Perfect negative correlation  | Always move in opposite directions               |

### **4. What to Look For**

- **Very High Positive Correlation (dark purple, close to +1):** May indicate duplication, linked drivers, or shared activity.
- **Unexpected Negative Correlation (dark purple near -1):** Could suggest conflicting transactions or errors.
- **No Correlation (white or pale):** Accounts are independent, as expected for unrelated functions.

---

## **Filtering the View**

When working with a large number of accounts, use the filter to narrow down the accounts displayed. This helps you focus on the accounts that matter most and examine their interrelationships.

1. Select the heatmap (1), then click on **Fields** (2) in the top-right corner to adjust the accounts shown.

    !!! example "Fields Filter"
        <iframe frameborder="0" style="width:100%;height:532px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Correlation%20Matrix.drawio&page-id=USqh03oqaenYsNgm5tcM&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1LkCCTe7vRbgLR58Dv9UhNTXtOvHhjLw1%26export%3Ddownload"></iframe>

2. Once you click on "Fields", a new sidebar will appear on the right side of the screen, you can then configure the accounts you want to include in the heatmap in both the Rows (3) and Columns (4) sections.

    !!! example "Configuring Fields"
        <iframe frameborder="0" style="width:100%;height:552px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Correlation%20Matrix.drawio&page-id=8y-5HbPV5T08NN3ezFjh&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1LkCCTe7vRbgLR58Dv9UhNTXtOvHhjLw1%26export%3Ddownload"></iframe>

3. Click on "Rows" or "Column" based on where you want to filter accounts then click on the edit icon (pencil) to open the filter options.

    !!! example "Editing Rows/Columns"
        <iframe frameborder="0" style="width:100%;height:496px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Correlation%20Matrix.drawio&page-id=dN3mE9X1821m-fTrqrIx&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1LkCCTe7vRbgLR58Dv9UhNTXtOvHhjLw1%26export%3Ddownload"></iframe>

4. a new pop-up will appear with two panels: "Available Members" (left) and "Current Set" (right).
    1. Use the "Available Members" Panel (Left):
        1. Browse or search for source accounts you want to include.
        2. Accounts are grouped hierarchically (e.g., 101000, 117000, 803000).
        3. Use the arrow button to select desired accounts.

    2. Add to the "Current Set" (Right Panel)
        1. The accounts on the right side are the ones currently included in the matrix.
        2. You can remove existing ones or add new ones from the left panel.

    3. Apply the Changes:
        1. Click “Apply and close” to update the matrix.
        2. The heatmap will regenerate to reflect the selected account combinations.