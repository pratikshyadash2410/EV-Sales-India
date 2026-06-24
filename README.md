# EV Sales India (2014-2024)🛵📈

This project presents a data driven analysis of Electric Vehicle (EV) sales in India, examining sales trends, state wise adoption patterns, vehicle segment performance and future demand projections through forecasting and machine learning techniques.

# Objective

- To evaluate monthly and yearly sales growth trends of EVs in India. 
- To compare state wise adoption patterns and identify leading regions. 
- To analyse the contribution of different vehicle types (2W, 3W, 4W, etc.). 
- To distinguish between passenger vs commercial adoption of EVs. 
- To build predictive models for forecasting future EV sales. 
- To derive business and policy insights that can help accelerate EV adoption in India.

# Tech Stack

- Programming Language: Python
- Data Analysis & Processing: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Time Series Forecasting: Holt Winters Exponential Smoothing
- Machine Learning Models: Scikit-learn, XGBoost Regressor
- Development Environment: Jupyter Notebook

# Data Preprocessing

The dataset was prepared for analysis through the following preprocessing steps:

- Inspected dataset structure and data types.
- Identified and handled missing values.
- Checked for duplicate records.
- Converted date fields to datetime format.
- Standardized categorical variables by removing inconsistencies and extra whitespace.
- Converted EV sales quantities to numeric format for analysis and modeling.

# Analysis Performed
• Monthly EV Sales Trend
- Analyzed monthly EV sales patterns to identify demand fluctuations and seasonal trends.

• Yearly EV Sales Trend
- Examined annual EV sales trends to understand market growth over time.

• State-Wise EV Sales Analysis
- Compared EV sales across Indian states to identify adoption patterns and leading markets.

• Vehicle Type Analysis
- Evaluated sales performance across different vehicle types.

• Vehicle Category Analysis
- Analyzed the contribution of various vehicle categories to overall EV sales.

• Vehicle Class Analysis
- Explored EV sales distribution across different vehicle classes.

# Forecasting

Implemented a Holt-Winters Exponential Smoothing model to forecast EV sales for the next 12 months using historical sales data.

• Forecast Output

- Historical sales trend visualization
- 12 month EV sales projection
- Trend and seasonality based forecasting

# Machine Learning Model

Developed an XGBoost Regressor to predict EV sales quantities.

• Model Workflow

- Feature engineering
- One hot encoding of categorical variables
- Train-test split
- Model training using XGBoost
- Performance evaluation using R² Score

# Evaluation Metrics

- Training R² Score - 
- Testing R² Score - 


# Key Insights

- EV adoption in India has shown a consistent upward trend, especially in the 
last few years.
- Certain states lead significantly in EV adoption (Uttar Pradesh, Maharashtra, 
and Delhi), while other states show slower penetration. 
- Two wheelers and three wheelers dominate the market, highlighting 
affordability and usage in urban as well as semi urban areas. 
- Four wheeler adoption is lower but steadily increasing, indicating a growing 
consumer shift towards private EVs. 
- The commercial vehicle category, particularly three wheelers show high 
adoption due to demand in shared mobility and delivery services. 
- The Linear Regression model achieved a Train score of 98.56% and Test 
score of 93.93%, confirming that EV sales can be reliably predicted using 
historical data. 
- The Holt Winters forecasting model projected strong sales growth for the 
next 12 months, further reinforcing the long-term upward trajectory of EV 
adoption in India.

# Reccommendations

- Governments should expand targeted subsidies, tax incentives, and charging infrastructure in low adoption regions to promote balanced EV growth across states.
- Automakers should strengthen their presence in the affordable EV segment, as these categories are key drivers of mass market adoption.
- Manufacturers can accelerate four-wheeler (4W) EV adoption by offering battery warranties, flexible financing options, and robust charging ecosystem support.
- Logistics and delivery companies should be encouraged to adopt three wheeler (3W) and light commercial vehicle (LCV) EVs for last mile transportation.
- Policymakers and industry stakeholders can leverage forecasting insights to support strategic production planning, supply chain management and infrastructure development.

# Project Files

- EV Sales.ipynb — Analysis notebook
- Electric Vehicle Sales.csv — Dataset

# Conclusion 

The analysis highlights India’s rapid shift towards electric mobility, driven by 
affordable 2W and 3W adoption and supported by state level initiatives. Predictive 
modelling further confirms that EV sales will continue to rise, underlining the 
importance of sustained policy support and infrastructure development.


