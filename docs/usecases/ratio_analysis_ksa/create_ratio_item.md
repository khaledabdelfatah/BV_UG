# **Creating Ratio Item**

This table describes all available columns when configuring a ratio item in the Ratio Analysis module.

| **Column Name**         | **Description** |
|-------------------------|-----------------|
| **Serial Number**       | A unique, incremental identifier for each ratio item. Used to maintain the order of items. |
| **Ratio Item**          | A descriptive label for the ratio line. It appears in correlation visualizations and reports. |
| **Numeric**             | When the ratio item is only a static numeric value. this column indicates the numeric value directly. |
| **Exclude**             | Marks the ratio item as temporarily inactive in the analysis. Useful for testing or iteration without deletion. |
| **Negate**              | Applies a negative sign to the value of the item. Commonly used when reversing values for comparative analysis. |
| **Income Statement**    | The income statement classification related to this ratio item. |
| **Balance Sheet**       | The balance sheet where this ratio item is classified. |
| **GS Group**            | The Group Statement category that this ratio item belongs to. |
| **FS Group**            | The Financial Statement grouping to categorize and report this item. |
| **Company**             | Identifies the company entity associated with this ratio item. |
| **Function**            | Indicates the business function (e.g., operations, marketing) related to the item. |
| **Account**             | Specifies the general ledger account associated with the ratio item. |
| **Period Type**         | Defines the reporting period type (e.g., YTD, monthly, quarterly) for this ratio. |
| **Product**             | Identifies the product to which the ratio item is linked. |
| **Project**             | Associates the ratio item with a specific project, if applicable. |
| **Network**             | Indicates the relevant network element tied to the ratio item. |
| **Customer**            | Specifies the customer related to this item, useful for customer-specific financial ratios. |
| **Function Group**      | Categorizes the item into a broader function group for hierarchical analysis. |
| **Account Group**       | Groups similar accounts together for consolidated reporting. |
| **Product Group**       | Groups related products for more streamlined ratio reporting. |
| **Balance Type**        | Defines how the balance is calculated or interpreted for the ratio item. Available options: <br><br> - **Average Balance**: Calculates the average between the opening and closing balances over a period.<br> - **Opening Balance**: Uses the starting balance at the beginning of the reporting period.<br> - **Movement**: Net change within the period (debits minus credits).<br> - **YTD Balance**: Aggregated balance from the start of the fiscal year up to the current period.|
| **Used In Group Ratio** | Indicates whether the ratio item is shared with other groups. Select **Yes** to enable sharing or **No** to keep it local. |


## Creating a New Ratio Item

To create a new ratio item, follow these steps:

1. Insert the serial number in the **Serial Number** field.  This is a unique identifier for the ratio item.

2. Enter the ratio item name in the **Ratio Item** field.  This is the name of the financial ratio you want to create.
3. Fill in the remaining fields as needed to define the ratio item fully.
4. Click on the "Create Ratio Item" button (1) to add a new row for the ratio item with the name you entered. Once you click on the button, the ration item will be created in the table , this might take 1-2 minutes to be created. once created and you can use it in the calculation of the ratio item.

!!! example "Create Ratio Item Button"
    <iframe frameborder="0" style="width:100%;height:357px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=ratio_analysis_ksa.drawio&page-id=pryP_8vYTykO-8-kc3v9&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1hKgOcEDgKFqvXKH_T1YuvhA6f-4lwTjP%26export%3Ddownload"></iframe>