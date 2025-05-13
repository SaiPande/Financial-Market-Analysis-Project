# *Financial Market Analysis Project*

## **Overview**
This project explores relationships between different financial datasets, including S&P 500 stocks, gold prices, real estate sales, and U.S. recessions. The goal is to identify patterns and correlations that can provide insights into economic trends.

## **Datasets Used**
S&P 500 Stocks: Daily stock prices for S&P 500 companies.<br>
S&P 500 Companies: Company details such as sector and financial metrics.<br>
Gold Prices: Historical gold prices with technical indicators.<br>
Real Estate Sales: Property sales data from 2001 to 2021.<br>
U.S. Recession: Monthly economic indicators, including GDP and unemployment rates.

## **Data Preprocessing**
Missing Values: Filled or removed based on column type.<br>
Outlier Handling: Applied IQR method.<br>
Normalization: Scaled numerical columns using MinMaxScaler.<br>
Encoding: Label encoded categorical columns.<br>
Feature Engineering: Extracted date-based features.<br>

## **Final Processed Files**
sp500_companies_cleaned.csv<br>
sp500_cleaned.csv<br>
GOLD_cleaned.csv<br>
RealEstate_cleaned.csv<br>
US_Recession_cleaned.csv<br>

## **Exploratory Data Analysis (EDA)**
Descriptive Statistics: Summary statistics for each dataset.<br>
Visualizations: Histograms, scatter plots, and correlation matrices.<br>
Correlation Analysis: Relationships between key variables.<br>

## **Tech Stack**
Programming Language: Python<br>
Libraries: Pandas, NumPy, SciPy, Scikit-Learn, Seaborn, Matplotlib<br>
Environment: Jupyter Notebook, Visual Studio Code

## Execution Instructions
### 1. Clone the Repository
```bash
git clone [https://github.com/SaiPande/Financial-Market-Analysis-Project.git](https://github.com/SaiPande/Financial-Market-Analysis-Project.git)
```
```bash
cd Financial-Market-Analysis-Project
```

### 2. Install Dependencies
```bash
pip install pandas numpy scipy scikit-learn seaborn matplotlib
```

### 3. Prepare the Data
Place raw datasets in the data/raw folder.<br>
Run the preprocessing scripts located in the preprocessing folder.

### 4. Run the Analysis
Open Jupyter Notebook:
Open and execute Milestone1.ipynb to generate descriptive statistics and visualizations.

### 5. View Results
Processed datasets are saved in the data/cleaned folder.<br>
Visualization outputs are saved in the outputs folder.

### 6. Feature Engineering, Feature Selection and Modeling
Open Jupyter Notebook:
Open and execute Milestone2.ipynb.
