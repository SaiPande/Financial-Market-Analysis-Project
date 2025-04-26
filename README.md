# H1 **Financial Market Analysis Project**

**Overview**
This project explores relationships between different financial datasets, including S&P 500 stocks, gold prices, real estate sales, and U.S. recessions. The goal is to identify patterns and correlations that can provide insights into economic trends.

**#Datasets Used**
S&P 500 Stocks: Daily stock prices for S&P 500 companies.
S&P 500 Companies: Company details such as sector and financial metrics.
Gold Prices: Historical gold prices with technical indicators.
Real Estate Sales: Property sales data from 2001 to 2021.
U.S. Recession: Monthly economic indicators, including GDP and unemployment rates.

**#Data Preprocessing**
Missing Values: Filled or removed based on column type.
Outlier Handling: Applied IQR method.
Normalization: Scaled numerical columns using MinMaxScaler.
Encoding: Label encoded categorical columns.
Feature Engineering: Extracted date-based features.

**#Final Processed Files**
sp500_companies_cleaned.csv
sp500_cleaned.csv
GOLD_cleaned.csv
RealEstate_cleaned.csv
US_Recession_cleaned.csv

**#Exploratory Data Analysis (EDA)**
Descriptive Statistics: Summary statistics for each dataset.
Visualizations: Histograms, scatter plots, and correlation matrices.
Correlation Analysis: Relationships between key variables.
Tech Stack
Programming Language: Python
Libraries: Pandas, NumPy, SciPy, Scikit-Learn, Seaborn, Matplotlib
Environment: Jupyter Notebook, Visual Studio Code

**#Execution Instructions**
#1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/SaiPande/cap5771sp25-project.git

cd cap5771sp25-project

#2. Install Dependencies
bash
pip install pandas numpy scipy scikit-learn seaborn matplotlib

#3. Prepare the Data
Place raw datasets in the data/raw folder.
Run the preprocessing scripts located in the preprocessing folder.

**#4. Run the Analysis**
Open Jupyter Notebook using:
bash
jupyter notebook
Open and execute EDA.ipynb to generate descriptive statistics and visualizations.

**#5. View Results**
Processed datasets are saved in the data/cleaned folder.
Visualization outputs are saved in the outputs folder.

**Please note that with the permission of Dr. Grant, I reduced my scope of project from real-estate, stock market and gold analysis to just the real-estate as the project was getting very complex to work with.**