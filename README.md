# Project-2_Tableau_Dashboard_Investment_Funds
## Investment Funds Dashboard on Tableau Public 
This repository contains a Tableau Public project to analyze and visualize data related to investment funds. The dataset consists of various tables containing information about funds, investors, investments, assets, transactions, performance, fees, managers, audits, and market data. 

### Data Ingestion and Preparation with Pandas To prepare the data for visualization, the following steps were taken using Pandas: 
1. **Data Ingestion**: The CSV files were ingested into Pandas DataFrames.
2. **Data Denormalization**: Additional denormalization was performed to explore and understand the data fully.
3. **Data Exploration**: The data was thoroughly investigated to identify any patterns or anomalies.
4. **Handling Missing Values**: Missing values were cleaned or imputed to ensure data quality.
### Risk Calculation and Assessment Risk assessment is crucial for investors to understand the potential variability of returns associated with each fund. The risk level for each fund was determined based on its volatility, typically measured by standard deviation (std) or variance (var) of the fund's performance. 
#### Calculating Standard Deviation (std) and Variance (var) Standard deviation and variance provide measures of the dispersion or variability of returns around the average (mean) return of a fund. A higher standard deviation or variance indicates greater volatility, which implies higher risk. 
#### Assessing Risk Levels The risk level for each fund was defined based on its volatility as follows: 
- **Low Risk**: Funds with a standard deviation (std) of performance below a certain threshold (5%) and a variance (var) below another threshold (10%) were classified as low risk.
- **Medium Risk**: Funds with a standard deviation (std) of performance between the low and high-risk thresholds were classified as medium risk
- **High Risk**: Funds with a standard deviation (std) of performance above a certain threshold (10%) or a variance (var) above another threshold (20%) were classified as high risk. By categorizing funds into risk levels, investors can make informed decisions based on their risk tolerance and investment objectives.
### Visualizations 
#### 1. General Overview of the Dataset: 'Investment Funds Overview' - Pie chart showing the distribution of asset types. - Bar chart showing the distribution of different asset types by fund type or across all funds. - Bar charts showing the top 5 funds by performance and their investment volumes. 
#### 2. Fund Performance and Investment Patterns: 'Investment Fund KPI' - Line chart showing the performance evolution of each fund compared to a market data reference index (NASDAQ). - Details of the selected fund. - Line charts showing the transaction count by transaction type over time. - Advanced table showing fund details (fees, amount invested, performance). 
### Additional Links - [Investment Funds Dashboard](https://public.tableau.com/app/profile/valeriia.paksivatkina/viz/Dashboard_Investment_Fund/InvestmentFundsOverview) 

Explore the visualizations and discover more about investment funds!
