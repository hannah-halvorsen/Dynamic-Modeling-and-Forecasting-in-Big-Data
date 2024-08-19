Housing in America: Predictive Time Series Models
Project Proposal by Hannah Halvorsen
CSCI E-116 Dynamic Modeling and Forecasting in Big Data
Harvard Extension School
Spring 2024

Project Overview
The housing market in the United States is a critical economic indicator with significant implications for policymakers, investors, lenders, and individuals. This project focuses on forecasting the Housing Price Index (HPI) using predictive time series models. By leveraging historical HPI data and other relevant economic variables, we aim to develop models that provide accurate forecasts of future HPI trends.

Problem Statement
The goal of this project is to develop predictive models that can accurately forecast fluctuations in the Housing Price Index (HPI). This will aid various stakeholders in making informed decisions and interventions based on anticipated market movements.

Value of the Project
This project offers substantial value to several groups:

Policymakers: Supports informed decisions related to housing policy, economic stability, and community development.
Researchers: Provides insights into housing market dynamics for academic analysis.
Lenders: Enhances risk assessment and investment strategies based on predicted HPI trends.
Individuals: Assists in understanding housing market trends for better decision-making in buying, selling, or investing in properties.
Data Summary
The HPI is derived from data on conventional conforming mortgage transactions collected from Freddie Mac and Fannie Mae. Key points include:

Data Source: FHFA House Price Index (HPI)
Methodology: Weighted-repeat sales (WRS) method by Case and Shiller (1989)
Base Period: Properties with at least two mortgages since January 1975
Constant Quality Index: Controls for variations in property quality
Geographic Coverage: National, U.S. Census divisions, and states
Update Frequency: Quarterly
Statistical Methods: Repeat sales method with multivariate regression
FRED Series Utilized
To explore relationships and predictive power of HPI, the following FRED series IDs will be used:

'UNRATE' - Unemployment Rate
'CPIAUCSL' - Consumer Price Index for All Urban Consumers: All Items
'PCE' - Personal Consumption Expenditures: Services
'MORTGAGE30US' - Mortgage Rates: 30-Year Fixed Rate
'PERMIT' - Building Permits
'GDP' - Gross Domestic Product
'MSPUS' - Median Sales Price of Houses Sold
'DSPIC96' - Real Disposable Personal Income
'RHORUSQ156N' - Homeownership Rate
'GS10' - 10-Year Treasury Constant Maturity Minus 2-Year Treasury Constant Maturity
'HSN1F' - New Privately-Owned Housing Units Authorized by Building Permits
'HOUST' - Housing Starts: Total New Privately Owned Housing Units Started
'WPSID62' - Number of Households: Owner Occupied Housing Units: Median Value
'PPICPE' - Producer Price Index by Commodity: All Commodities
'CSCICP03USM665S' - Consumer Sentiment Index
'POP' - Population
'CP' - Construction Payroll Employment
'CUMFNS' - Capacity Utilization: Manufacturing
Methodology
Data Collection: Import data using the Fred library.
Data Preparation: Clean and preprocess the data for analysis.
Exploratory Data Analysis (EDA): Analyze historical trends and relationships between HPI and other variables.
Model Development: Build and validate time series models such as ARIMA, Exponential Smoothing, and machine learning techniques.
Evaluation: Assess model performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.
Forecasting: Generate forecasts and visualize future HPI trends.
