
# Dashboard Components

## **Overview**

The dashboard consists of several components that provide insights into the data. The main components are:

- Top 10 Categories by Number of Anomalies.
- Top 10 Sources by Number of Anomalies.
- Number of Anomalies by Value Risk.

??? question "What's the difference between 'Value Rank' and 'Risk Rank'?"
    - **Value Rank**: Indicates how unusual a value in a journal entry (JE) is compared to typical values. For example, if the usual value is 1,000 but this time it is 10,000, the Value Rank highlights this anomaly (e.g., high, medium, low).
    - **Risk Rank**: Represents the AI model's assessment of risk, combining multiple factors such as Value Rank, Source Rank, and Category Rank. Anomalies are flagged and displayed on the dashboard based on this ranking.


---

### Anomalies Table

The Anomalies table is a detailed view of the anomalies detected in the data. It includes the following columns:

- **Group Statement (CS) Group**: It holds 3 values you can include in your analysis:
    - **Cost of Services**
    - **Sales & Marketing Expenses**
    - **General & Admin Expenses**