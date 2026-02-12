# Credit-Card-Fraud-Risk-Analysis

#### Project Overview :-
This project delivers a comprehensive and interactive Credit Card Fraud Risk Analysis Dashboard designed to monitor fraudulent transactions, assess risk exposure, and identify critical fraud patterns across transaction types, geographies, and time. The objective is to help financial institutions and risk teams detect high-risk transactions early, understand dominant fraud methods, and support data-driven fraud prevention strategies.

#### Explore the interactive dashboard here :-
Credit Card Fraud Risk Analysis Dashboard – [Power BI](https://app.powerbi.com/reportEmbed?reportId=7a8d7ed8-c93e-4104-be3b-f713fe51be1c&autoAuth=true&ctid=6ae61906-14a5-49ea-96fd-b668374609d4)

#### Tools Used :-
* Power BI – Interactive data visualization & dashboard design
* Excel / CSV – Data preprocessing and validation
* DAX – Measures and calculated KPIs for fraud metrics
* Data Modeling – Relationship building and aggregation

#### Dataset / Input Data :-
The dashboard is built using credit card transaction data, including:
* Transaction Details: Transaction_ID, Transaction_Date, Transaction_Amount
* Fraud Information: Fraud_Type, Fraud_Flag
* Risk Classification: Low, Medium, High, Critical
* Merchant Details: Merchant_Name, Transaction_Category
* Geographic Data: State

#### What the Dashboard Shows :-
1. Key Metrics & KPIs
2. Fraud Rate – 28.60%
3. Total Fraudulent Transactions – 286
4. Critical Risk Transactions – 10.70%
5. Total Fraud Amount – ₹3M
6. Top Fraud Type – Card Not Present

#### Highlights :-
* Dominant Fraud Type: Card Not Present (CNP) transactions contribute the highest fraudulent amount, indicating increased risk in online payments.
* Risk Distribution: Low-risk transactions form the largest share (42.42%), but nearly 30% fall under Medium risk, requiring active monitoring.
* High-Risk Categories: E-commerce and Electronics transactions show consistently higher fraud exposure across fraud types.
* Geographic Concentration: Maharashtra, Karnataka, and Rajasthan record the highest number of fraudulent transactions.
* Seasonal Trend: Fraud activity spikes during mid-year and peaks again in December, indicating possible festive or year-end misuse patterns.

#### Output :-
* Card Not Present fraud is the primary risk driver, demanding stronger online transaction controls.
* A significant portion of transactions lie in Medium–Critical risk bands, highlighting the need for proactive risk scoring.
* Certain states consistently report higher fraud counts, enabling region-focused fraud mitigation strategies.
* Month-wise trends reveal predictable spikes that can be used for preventive monitoring and alerting.

#### Conclusion :-
The analysis reveals a substantial concentration of fraud in online transactions, particularly Card Not Present payments, with clear geographic and seasonal patterns. While a large share of transactions is classified as low risk, the meaningful presence of Medium and Critical risk transactions poses a serious operational threat. Strengthening fraud detection for e-commerce channels, implementing region-specific controls, and deploying time-based monitoring can significantly reduce fraud exposure and financial losses.
