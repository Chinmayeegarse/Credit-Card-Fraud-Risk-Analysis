# Credit-Card-Fraud-Risk-Analysis

#### Project Overview :-
This project presents an interactive Credit Card Fraud Risk Analytics Dashboard built to identify fraud patterns, assess financial risk exposure, and support data-driven fraud prevention strategies.

The analysis covers 1,000+ transactions across 9 banks, uncovering key fraud drivers, high-risk regions, and time-based fraud trends.

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
Key Metrics & KPIs
1. Total Transaction Amount - $12.23M
2. Fraud Rate - 27.05%
3. Total Fraudulent Transactions – 286
4. Critical Risk Transactions – 10.70%
5. Total Fraud Amount – ₹3.31M

## Dashboard Preview

### Executive Summary
![Dashboard1](Screenshots/dashboard1.png)

### Fraud Analysis
![Dashboard2](Screenshots/dashboard2.png)

### Geographic Analysis
![Dashboard3](Screenshots/dashboard3.png)




#### Highlights :-
* Digital Channel Vulnerability: Card Not Present (CNP) fraud serves as the primary tactical risk driver (72 incidents), proving that immediate multi-factor authentication and digital checkout security upgrades are non-negotiable for online processing channels.
* Critical Exposure Management: A massive portion of transactional value sits exposed in the Medium to Critical risk bands (representing over ₹1.57M in financial exposure), highlighting the need for live, pre-settlement risk scoring rather than post-fraud detection.
* Geofenced Mitigation Strategies: Regional analytics isolate Karnataka, Maharashtra, and Rajasthan as high-density fraud corridors crossing a critical 30% fraud rate. Risk teams can use this output to deploy localized velocity limits and targeted merchant audits in these states.
* Sector-Specific Resource Allocation: High-leakage sectors like Food Delivery (32.01%) and E-commerce (29.90%) require immediate transactional value caps and stricter verification protocols compared to safer sectors like Food Delivery or Groceries.
* Predictive Alerting Framework: The predictable, recurring mid-year spikes and December festive surges identified on the temporal timeline allow the institution to dynamically scale up monitoring sensitivity and defensive fraud filters right before peak risk windows hit.

#### Conclusion :-
The analysis reveals a substantial concentration of fraud in online transactions, particularly Card Not Present payments, with clear geographic and seasonal patterns. While a large share of transactions is classified as low risk, the meaningful presence of Medium and Critical risk transactions poses a serious operational threat. Strengthening fraud detection for e-commerce channels, implementing region-specific controls, and deploying time-based monitoring can significantly reduce fraud exposure and financial losses.
