# PhonePe Transaction Analytics Dashboard

## Project Overview
This project is an interactive Power BI dashboard designed to analyze PhonePe-style digital payment activity across multiple financial services.

The dashboard provides a consolidated view of transaction activity and then allows deeper analysis across:

- Insurance
- Loans
- Money Transfer
- Recharge & Bills

The objective is to turn transaction-level data into a business-friendly dashboard that helps users understand transaction volume, transaction value, payment status, service performance, transaction reasons, monthly trends, and service/type-level patterns.

> **Note:** This is a analytics project. The dashboard should not be interpreted as an official PhonePe business report unless the underlying dataset is officially sourced and authorized.
-----


## Dashboard Pages
The Power BI file contains five main pages:

1. **Home** – Overall transaction overview and cross-service analysis
2. **Insurance** – Insurance premium and transaction analysis
3. **Loans** – Loan amount and loan-type analysis
4. **Money Transfer** – Money-transfer value, status, reason, and transfer-type analysis
5. **Recharge & Bills** – Recharge/bill payment value, status, reason, and recharge-type analysis
-----

## Business Problem
Digital payment platforms generate large volumes of transactions across different services. A business analyst needs a clear way to answer questions such as:

- How many transactions are taking place?
- What is the total transaction value?
- How are transactions distributed across services?
- Which services contribute the most transaction value?
- How does transaction activity change over time?
- What are the major transaction reasons?
- What proportion of transactions are successful or failed?
- Which insurance, loan, transfer, or recharge categories contribute the most value?

This dashboard brings these questions into a single interactive analytical view.
-----


## Business Questions

### Overall / Home
1. What is the total number of transactions?
2. What is the total transaction amount?
3. How many successful transactions are recorded?
4. How many failed transactions are recorded?
5. How does transaction value change by month?
6. Which service contributes the highest transaction value?
7. What are the most common transaction reasons?

### Insurance
1. What is the total insurance premium amount?
2. How does insurance premium value change over time?
3. What is the transaction/reason distribution?
4. What is the payment-status distribution?
5. Which insurance type contributes the highest premium value?
6. How do Bike, Car, Term Life, and Health insurance compare?

### Loans
1. What is the total loan amount?
2. How does loan value change by month?
3. What is the payment-status distribution?
4. What are the major loan-related transaction reasons?
5. Which loan type contributes the highest loan amount?
6. How do Gold Loan, Auto Loan, Mutual Funds, and Credit Score-related categories compare?

### Money Transfer
1. What is the total money-transfer amount?
2. How does transfer value change by month?
3. What are the most common transfer reasons?
4. What is the payment-status distribution?
5. Which transfer type contributes the highest transaction value?
6. How does transaction activity vary over time?

### Recharge & Bills
1. What is the total recharge and bill-payment amount?
2. How does payment value change by month?
3. What is the payment-status distribution?
4. What are the major payment reasons?
5. Which recharge/bill type contributes the highest amount?
6. How do Electricity, Mobile, DTH, and Cable TV compare?
-----

## Key KPIs

### Overall Dashboard
| KPI                     | Purpose                                    |
|-------------------------|--------------------------------------------|
| Total Transactions      | Measures overall transaction volume        |
| Successful Transactions | Measures completed transaction activity    |
| Failed Transactions     | Measures unsuccessful transaction activity |
| Total Amount            | Measures total transaction value           |

### Service-Level KPIs
| Service          | Main KPI              |
|------------------|-----------------------|
| Insurance        | Total Premium         |
| Loans            | Total Loan Amount     |
| Money Transfer   | Total Transfer Amount |
| Recharge & Bills | Total Payment Amount  |

Additional analytical dimensions include payment status, transaction reason, service/type, and monthly transaction value.
-----


## Data Model / Analytical Dimensions

The report uses service-specific analytical areas including:
- `All_Transactions`
- `Insurance`
- `Loans`
- `Money_Transfer`
- `Recharge_Bills`

Important fields visible in the report include:
- Date
- Transaction ID
- Amount
- Reason
- Payment Status
- Service
- Insurance Type
- Loan Type
- Transfer Type
- Recharge Type
- Premium
- Loan Amount
------

## Analysis Workflow
The project follows a typical data-analysis workflow:

1. **Data Collection** – Transaction/service data is used as the analytical source.
2. **Data Preparation** – Data is prepared for reporting and analysis.
3. **Data Modeling** – Service-specific tables and analytical fields are organized for Power BI.
4. **Measure Creation** – Transaction amount and transaction-count metrics are used in the dashboard.
5. **Visualization** – KPIs, trends, categorical comparisons, and status analysis are presented through Power BI visuals.
6. **Business Analysis** – The dashboard is used to identify trends, high-value categories, and transaction-status patterns.
-----

## Dashboard Preview
Add screenshots of your final dashboard here:

```text
screenshots/
├── home.png
├── insurance.png
├── loans.png
├── money-transfer.png
└── recharge-bills.png
```
------

## Key Insights
The final insights should be written from the actual numbers shown in the dashboard. Avoid inventing values.

Recommended insight format:
### 1. Overall Transaction Performance
- Total transaction volume: **[insert value]**
- Total transaction value: **[insert value]**
- Successful transactions: **[insert value]**
- Failed transactions: **[insert value]**

### 2. Service Performance
- Highest-value service: **[insert service]**
- Highest transaction-volume service: **[insert service]**
- Lowest/highest contribution: **[insert result]**

### 3. Monthly Trend
- Highest transaction-value month: **[insert month]**
- Lowest transaction-value month: **[insert month]**
- Major increase/decrease period: **[insert period]**

### 4. Insurance
- Highest-value insurance type: **[insert type]**
- Dominant payment status: **[insert status]**
- Highest-premium period: **[insert month]**

### 5. Loans
- Highest-value loan category: **[insert type]**
- Highest loan-value month: **[insert month]**
- Dominant payment status: **[insert status]**

### 6. Money Transfer
- Highest-value transfer type: **[insert type]**
- Highest transfer-value month: **[insert month]**
- Dominant payment status/reason: **[insert result]**

### 7. Recharge & Bills
- Highest-value recharge/bill category: **[insert type]**
- Highest payment-value month: **[insert month]**
- Dominant payment status: **[insert status]**
-----

## Tools & Technologies

- Microsoft Power BI
- Data Visualization
- Excel data source
-----

## Project Structure

```text
PhonePe-Transaction-Analytics-Dashboard/
│
├── README.md
│
├── powerbi/
│   └── PhonePe_Transaction_Analytics.pbix
│
├── data/
│   └── Phonepe_Final_Dataset.xlsx
│
├── screenshots/
│   ├── home.png
│   ├── insurance.png
│   ├── loans.png
│   ├── money-transfer.png
│   └── recharge-bills.png
│
└── documentation/
    └── data_dictionary.md
```
------

## How to Use
1. Download `PhonePe_Transaction_Analytics.pbix`.
2. Open it using Microsoft Power BI Desktop.
3. If the original data source is not embedded/available, update the data-source path.
4. Refresh the dataset.
5. Use the page navigation and filters/slicers to explore the dashboard.
-----

## Portfolio Value
This project demonstrates practical data-analysis skills including:

- Business-question formulation
- KPI design
- Data modeling
- Power Query
- DAX-based analysis
- Time-series analysis
- Category analysis
- Status analysis
- Interactive dashboard design
- Business insight generation
-----

## Author
**Sourabh Mondal**

Data Analysis | Power BI | SQL | Excel | Python
---

## Disclaimer
This project is created for educational and portfolio purposes. Any dataset used should be properly attributed and should not contain confidential or personally identifiable information.
#   P h o n e P e - T r a n s a c t i o n - A n a l y t i c s - D a s h b o a r d 
