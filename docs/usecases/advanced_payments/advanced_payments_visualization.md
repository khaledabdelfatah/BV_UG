# **Advanced Payments Visualization**

## **Available Charts**

The **Advanced Payments Dashboard** provides a set of visualizations to help users understand the relationship between General Ledger (GL) balances and prepayments.

!!! example "Available Charts"
    <iframe frameborder="0" style="width:100%;height:1086px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Advanced%20Payments.drawio&page-id=3Z0t8OnM874MAqX8Oe6p&transparent=1&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1BCh7WuihrrMysr7j9V05zk8p6AI6JoJQ%26export%3Ddownload" allowtransparency="true"></iframe>

### **18220 GL vs Prepayments**

The **18220 GL vs Prepayments** bar chart provides a visual representation of the relationship between the General Ledger (GL) balance and prepayment amounts for the GL account **18220**. This chart is essential quickly identify discrepancies or inconsistencies in financial records.

### **18246 GL vs Prepayments**

The **18246 GL vs Prepayments** bar chart serves a similar purpose as the previous one, but it focuses on the GL account **18246**. By comparing the GL balance with prepayment amounts, users can gain insights into the financial status of this specific account.

### **Prepayment Balance By Year**

The **Prepayment Balance By Year** line chart illustrates the annual trends in prepayment balances. It provides a clear view of how prepayment amounts have changed over the years, helping users identify periods of increased financial activity or delays in application. This trend analysis is valuable for strategic planning and decision-making.

## **Prepayment Details Table**

The **Prepayment Details** section (1) of the Advanced Payments Dashboard provides a comprehensive overview of prepayment transactions. It includes detailed information about each prepayment, allowing users to analyze and manage their financial commitments effectively.

!!! example "Prepayment Details Table"
    <iframe frameborder="0" style="width:100%;height:1101px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Advanced%20Payments.drawio&page-id=wfZBhOQVN60zI07BCpfm&transparent=1&dark=auto#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1BCh7WuihrrMysr7j9V05zk8p6AI6JoJQ%26export%3Ddownload" allowtransparency="true"></iframe>

| **Column Name**                         | **Description** |
|-----------------------------------|-----------------|
| **Prepayment**                    | Displays the prepayment identifier. By default, all prepayments are shown. |
| **GL Account**                    | Shows the General Ledger (GL) account number linked to the prepayment. |
| **Prepayment Purchasing Order**   | Indicates the purchasing order associated with the prepayment. |
| **Supplier**                      | Name of the supplier to whom the prepayment was made. |
| **Year of Prepayment**            | Indicates the calendar year in which the prepayment occurred. |
| **Month of Prepayment**           | Indicates the calendar month of the prepayment. |
| **Day of Prepayment**             | Indicates the calendar day on which the prepayment was recorded. |
| **Days Since Invoice**            | Number of days since the related invoice was issued. Values exceeding the defined threshold are highlighted in red. |
| **Days Since Receipt**            | Number of days since the goods receipt was recorded. Red highlight appears if the value exceeds the set threshold. |
| **Prepayment Number**             | Unique reference number of the prepayment transaction. |
| **Prepayment Purchasing Order Number** | Displays the purchasing order number. A single prepayment may be linked to multiple POs. |
| **Prepayment Amount (SAR)**       | Total value of the prepayment in Saudi Riyals (SAR). |
| **Applied Amount (SAR)**          | Portion of the prepayment that has been utilized or matched to invoices. |
| **Balance (SAR)**                 | Remaining unapplied amount from the prepayment (i.e., Prepayment Amount - Applied Amount). |
| **Receipt Date**                  | Date on which the goods or services were officially received. |
| **Invoice Date**                  | Date on which the supplier’s invoice was issued. |
| **Prepayment Date**               | Date the prepayment transaction was executed. |
| **Prepayment Description**        | Provides contextual details about the nature or purpose of the prepayment. |

!!! Question "Why are some values highlighted in red in the Days Since Invoice and Days Since Receipt columns?"
    Red highlights in the **Days Since Invoice** and **Days Since Receipt** columns signify values that exceed predefined thresholds. These visual cues help users quickly identify prepayments requiring further investigation or immediate attention.