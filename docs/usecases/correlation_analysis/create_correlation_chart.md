# **Creating a Correlation Chart**

## **Overview**


The **Create Correlation Chart** tab is where you define how your correlation chart should be structured. Here, you select which correlation lines to include, whether any should be negated, and whether the chart should be made available to others.

!!! note "This tab is for setting up the chart definition. The actual chart will be generated in the next tab, **Correlation Analysis**."

## **How It Works**

This tab displays a table populated from the correlation group you created earlier. You can review, edit, or add new correlation lines directly in the table. Each row represents a correlation entry, which will be used to build the chart later.

You can edit line names and chart labels as needed, or create new entries from scratch.

!!! example "Create Correlation Chart Tab"
    <iframe src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%205.drawio&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1XU8TC-9GYGWZ_bXdaGy928SGd0uK35UO%26export%3Ddownload" width="100%" height="400px"></iframe>


### **Field Descriptions**
 | Field               | Description                                                                                                 | Required |
|--------------------|-------------------------------------------------------------------------------------------------------------|----------|
| **Correlation Chart** | The name of the chart group. If multiple rows share this name, their lines will be grouped into one chart. | Yes      |
| **Correlation Line**  | The name of the metric or value to be analyzed (e.g., “Nat Rev”). Typically defined in the previous step. | Yes      |
| **Negate**            | Set to **Yes** to reverse the value of the line in the final chart.                                        | Optional |
| **Publish**           | Set to **Publish** to share the chart with other users. Only admin users can change this field.            | Yes      |

---

## **Creating a New Correlation Chart**

To create a new correlation chart, follow these steps:

1. **Scroll to the bottom of the table.**
    - A new empty row is available for input.

2. **Add new correlation items.**
    - Enter the *Correlation Chart* name.
    - Enter the *Correlation Line* name.
    - Set the "Negate" field to **Yes** if you want to reverse the value of this line in the chart.

3. **Click the "Create Correlation Chart" button** (located at the top-left of the page).
    - A confirmation popup appears at the top-right of the screen indicating the creation process is underway.
    - Once the process is complete, a success message will be displayed.
    - You may cancel the operation at any point using the "Cancel" button.

    !!! example "Creating Correlation Chart Button"
        <iframe src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%205.drawio&page-id=5D_NAuSYNiDFtHeQa2m8&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1XU8TC-9GYGWZ_bXdaGy928SGd0uK35UO%26export%3Ddownload" width="100%" height="400px"></iframe>


## **Publishing a Correlation Chart**

!!! Warning inline end "**Only admin users** can publish charts to be shared with others."

Once you have created a correlation chart, you can choose to publish it for other users to view. This is done by setting the *Publish* field to **Publish**. To publish a chart:

1. Set the *Publish* field to **Publish** in the table.
2. Click the **Publish** button.

Once published, the chart becomes available in the **Shared Correlation Analysis** tab for other users to view (read-only access).


!!! example "Publishing Correlation Chart Button"
    <iframe src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Installation%20Guide%205.drawio&page-id=umuloliwBJ3-UckuWK2A&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1XU8TC-9GYGWZ_bXdaGy928SGd0uK35UO%26export%3Ddownload" width="100%" height="400px"></iframe>


