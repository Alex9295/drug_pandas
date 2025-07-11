## Drug Overdose Death Rates Analysis 
📊 Exploratory analysis of U.S. drug overdose death rates using CDC WONDER data.


📌 Overview
This project analyzes trends in drug overdose deaths in the United States from 1999 to 2020, focusing on:

Opioids (any, prescription, synthetic)

Cocaine

Heroin

The Jupyter notebook (Data9.ipynb) includes data loading, basic statistics, and visualizations (e.g., a pie chart of yearly distributions).


📂 Dataset
File: drug-overdose-death-rates-new.csv
Source: CDC WONDER (Centers for Disease Control and Prevention)

Columns:
Column Name	Description
Entity	Country (United States)
Code	Country code (USA)
Year	1999–2020
Any opioid death rates	Deaths per 100,000 (CDC WONDER)
Cocaine overdose death rates	Deaths per 100,000
Heroin overdose death rates	Deaths per 100,000
Synthetic opioids death rates	Deaths per 100,000
Prescription Opioids death rates	Deaths per 100,000
🔍 Key Insights (Preview)
Yearly Distribution:

Pie chart showing the proportion of data entries per year.

(Expandable with trends/peaks in specific drug categories.)

Statistical Summary:

Pandas’ describe() used to show mean, min/max death rates, etc.

🛠️ Setup & Usage
Prerequisites
Python 3.8+

Libraries: pandas, matplotlib, jupyter

Installation
bash
git clone https://github.com/yourusername/drug-overdose-analysis.git  
cd drug-overdose-analysis  
pip install -r requirements.txt  # Install dependencies  
Run the Notebook
bash
jupyter notebook Data9.ipynb  
📈 Future Enhancements
Add time-series plots for death rate trends.

