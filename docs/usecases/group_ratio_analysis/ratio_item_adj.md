# **Ratio Item Adjustment Tab**

The **Ratio Item Adjustment** tab is the primary interface for entering and adjusting raw financial data used in Group Ratio Analysis. It enables users to input or modify values for each financial line item across legal entities, business units, or cost centers. All group items created for STC subsidiaries are displayed here, allowing users to add or adjust values as needed.

!!! example "Ratio Item Adjustment Tab"
    <iframe frameborder="0" style="width:100%;height:472px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Ratio%20Item.drawio&page-id=cKHE-YoPmvJpchyAIUJD&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ViQwJ7Ct2HkwjA43M8LpeCm888kdrd0S%26export%3Ddownload"></iframe>
This tab supports manual input, validation, and override of financial data (e.g., revenue, net income, total assets) for a specific year, month, and scenario. The entered data is used in subsequent ratio calculations and analytics dashboards.

---

## **Changing the View**

- **PRA:** By default, all PRA items are displayed. You can toggle the view between `None` and `PRA`.
- **Year:** Select the desired year to view or input data. The system displays financial line items for the selected year.
- **Ratio M:** (Description needed.) !!!OMAR, please provide details for this field.
- **Ratio Item Version:** Choose between `Adjusted` and `As is` versions:
    - **As is:** Displays original data from the database without adjustments.
    - **Adjusted:** Allows users to modify data for analysis or reporting. You can replace, add, or subtract values.
- **Scenario:** Select a scenario such as Actual, Budget, Forecast, or quarterly forecasts (Q1, Q2, Q3) to analyze different financial situations.
- **Month:** Select the month to view or input data for that period.

!!! example "View Options"
    <iframe frameborder="0" style="width:100%;height:372px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Analysis%20-%20Ratio%20Item.drawio&page-id=a0szzbcLYjXwsZLPEPxL&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ViQwJ7Ct2HkwjA43M8LpeCm888kdrd0S%26export%3Ddownload"></iframe>

---

## **Adjusting a Value**

To modify a value, ensure you are in the **Adjusted** view for the relevant year, month, scenario, and ratio item version.

1. Locate the row for the financial line item you wish to adjust.
2. Right-click the value cell and select **Spread Data** (1) to open the data spread dialog.

    !!! example "Spread Data Dialog"
        <iframe frameborder="0" style="width:100%;height:507px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ration%20Analysis%20-%20Ratio%20Item%20Adj.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1TB0Rk055t4SSqPtFIBLl60QPynY9a03k%26export%3Ddownload"></iframe>

3. Enter the new value in the cell (2).
4. Set the update action (3):
     - **Replace:** Overwrite the existing value.
     - **Add:** Add the new value to the existing one.
     - **Subtract:** Subtract the new value from the existing one.
    
5. Click **Apply** button (4) to save your changes.

!!! example "Adjusting a Value"
    <iframe frameborder="0" style="width:100%;height:612px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ration%20Analysis%20-%20Ratio%20Item%20Adj.drawio&page-id=gYylk7N3Rd66M5e88_0l&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1TB0Rk055t4SSqPtFIBLl60QPynY9a03k%26export%3Ddownload"></iframe>

### **Adding a Comment**

To provide context for your adjustment, you can add a comment:

1. Right-click the value cell again after applying your changes.
2. Select **Comments** and then **Add Comment**.

    !!! example "Add Comment Dialog"
        <iframe frameborder="0" style="width:100%;height:482px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ration%20Analysis%20-%20Ratio%20Item%20Adj.drawio&page-id=AQkz6OFUj-USg6ggjFVc&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1TB0Rk055t4SSqPtFIBLl60QPynY9a03k%26export%3Ddownload"></iframe>

3. Enter your explanation (2) (e.g., "Adjusted by adding 3,232,843 because of new data").
4. Click **Post** (3) to save the comment.

    !!! example "Post a Comment"
        <iframe frameborder="0" style="width:100%;height:551px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ration%20Analysis%20-%20Ratio%20Item%20Adj.drawio&page-id=LVhRgq5bMvCgMhBWl0TJ&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1TB0Rk055t4SSqPtFIBLl60QPynY9a03k%26export%3Ddownload"></iframe>

The cell will display a comment icon, indicating that a note is associated with the value.

---

## **Deleting a Ratio Item**

To delete a ratio item:

1. Click the **Delete Item** button at the top right of the table.

    !!! example "Delete Item Button"
        <iframe frameborder="0" style="width:100%;height:613px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Item%20-%20Ratio%20Calculation.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1P2qWGyVw6flOV0dL2pWaF6VTQkrv2LLd%26export%3Ddownload"></iframe>

2. In the "Review Parameters for Ratio Item HFM Delete" popup, enter the exact name of the ratio item to delete.

    !!! example "Delete Popup"
        <iframe frameborder="0" style="width:100%;height:531px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Item%20-%20Ratio%20Calculation.drawio&page-id=hwnFHGNrB7advioPn1ID&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1P2qWGyVw6flOV0dL2pWaF6VTQkrv2LLd%26export%3Ddownload"></iframe>

3. Click **OK** to confirm.

The system will remove the specified ratio item and all associated data from the table.

---

## **Updating the View**

The **Review Parameters for Ratio Update Adj** dialog allows targeted updates to ratio data, improving performance and precision by refreshing only selected portions of the analysis table.

To update the view:

1. Ensure you are in the **Adjusted** view for the relevant year, month, scenario, and ratio item version.

2. Click the **Update View** button at the top right of the table.

    !!! example "Update View Button"
        <iframe frameborder="0" style="width:100%;height:613px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Item%20-%20Ratio%20Calculation.drawio&page-id=GsITu-8c83xJevJzetaA&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1P2qWGyVw6flOV0dL2pWaF6VTQkrv2LLd%26export%3Ddownload"></iframe>

3. In the **Review Parameters for Ratio Update Adj** popup, specify the parameters to control the update scope.
4. Click **OK** to apply the changes.

**Update Scope Controls:**

| Parameter   | Purpose                                  | Usage                                                      |
|-------------|------------------------------------------|------------------------------------------------------------|
| Month       | Limit updates to a specific month        | Enter the target month to refresh only that period's data  |
| Year        | Restrict updates to a particular year    | Specify the year to update annual or period-specific data  |
| Ratio Item  | Update only the selected ratio metric    | Choose a specific ratio to refresh its calculations        |
| Subsidiary  | Target updates for a specific entity     | Select the subsidiary to update only that entity's data    |

!!! example "Update View Dialog"
    <iframe frameborder="0" style="width:100%;height:460px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Group%20Ratio%20Item%20-%20Ratio%20Calculation.drawio&page-id=3SHzlC_xs2Iz24hsb9zb&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1P2qWGyVw6flOV0dL2pWaF6VTQkrv2LLd%26export%3Ddownload"></iframe>

!!! info "You must specify at least one parameter to update the data. You can also combine parameters to further narrow the update scope."

