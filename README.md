# Bank-Loan-Dashboard-Project
## Overview
The dashboard is created in Tableau serve to enhance data-driven decision-making, allowing for strategic planning in the lending operations of the bank.

## Dashboards
### Dashboard 1: Summary
![SUMMARY](https://github.com/impvn/BANK-LOAN-DATA-EDA-KPIs-Dashboard/assets/98079170/b6b169cd-e751-4dea-8edf-4d8f83ec3937)

The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:

* Total Loan Applications (MTD and MoM)
* Total Funded Amount (MTD and MoM)
* Total Amount Received (MTD and MoM)
* Average Interest Rate (MTD and MoM)
* Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.

### Dashboard 2: Overview
![OVERVIEW](https://github.com/impvn/BANK-LOAN-DATA-EDA-KPIs-Dashboard/assets/98079170/e01ab04d-4a6a-4f88-87cc-52c895c08969)


The Overview Dashboard visually represents various loan-related metrics through different chart types:

* Monthly Trends by Issue Date (Area Chart)
* Regional Analysis by State (Filled Map)
* Loan Term Analysis (Donut Chart)
* Employment Length Analysis (Bar Chart)
* Loan Purpose Breakdown (Bar Chart)
* Home Ownership Analysis (Tree Map)

These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details
![DETAILS](https://github.com/impvn/BANK-LOAN-DATA-EDA-KPIs-Dashboard/assets/98079170/a2eecf79-e6d3-4388-9655-fdfc6294659d)

The Details Dashboard offers a detailed view of the loan data, providing a comprehensive and user-friendly interface for accessing vital loan metrics, borrower profiles, and performance data.

### Data Fields and Usage
The data utilized in the dashboards comprise several fields, each serving a specific purpose in loan management and risk assessment:

* Loan ID: Unique identifier for loans.
* Address State: Borrower location for regional analysis.
* Employment Length: Indicates employment stability.
* Employee Title: Job title for income source verification.
* Grade/Sub Grade: Creditworthiness and risk classification.
* Home Ownership: Housing status for financial stability assessment.
* Issue Date: Loan origination date.
* Loan Status: Current state of the loan for performance tracking.
* Purpose: Loan reason for segmentation and customization.
* Term: Loan duration.
* Verification Status: Status of financial information verification.
* Annual Income: Yearly earnings for creditworthiness.
* DTI: Debt burden relative to income.
* Instalment: Monthly repayment amount.
* Interest Rate: Cost of borrowing.
* Loan Amount: Principal amount borrowed.

Each field plays a crucial role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.

## Implementation
The project involved loading the dataset from MySQL Server into Tableau. The dashboards were created using Tableau's visualization tools, adhering to the requirements outlined in the problem statement and leveraging the data dictionary for accurate field usage.

## Data Validation
To ensure the accuracy and integrity of the data reflected in the dashboards, a thorough data validation process was undertaken. After the dataset was loaded into Tableau from the MySQL Server, the following measures were implemented:

* SQL Query Verification: Direct queries were run against the MySQL Server database to fetch raw data. This data served as a benchmark to validate the data presented in the dashboards.

* Data Consistency Checks: The results from Tableau was compared against the SQL query results to ensure consistency. This step was critical to confirm that the data transformation and logic applied within Tableau did not alter the actual figures.

* KPI Logic Validation: The calculations and logic that underpin the KPIs were meticulously reviewed. SQL scripts were used to replicate the KPI calculations independently, verifying that the tableau computations was correct and reliable.

* Cross-Verification with Source Data: The transformed data was cross-verified with the source data from the MySQL Server database. This step was crucial to confirm that all data transformations, including filtering, grouping, and aggregation, were correctly applied.

Through these validation steps, the project ensured that the dashboards accurately represent the data and the insights derived are based on truthful and unaltered information. This rigorous validation process enhances the credibility of the dashboards and reinforces confidence in the data-driven decisions made using these tools.

## Conclusion
With the inclusion of robust data validation techniques, the Bank Loan Dashboard project stands as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions.
