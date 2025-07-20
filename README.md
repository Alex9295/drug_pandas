# Drug Overdose Death Rates Analysis 📊
Exploratory analysis of U.S. drug overdose death rates using CDC WONDER data (1999-2020).

## Table of Contents
- [Overview](#-overview)
- [Dataset](#-dataset)
- [Key Insights](#-key-insights)
- [Setup & Usage](#%EF%B8%8F-setup--usage)
- [Future Enhancements](#-future-enhancements)

## 📌 Overview
This project analyzes trends in drug overdose deaths in the United States from 1999 to 2020, with focus on:

- Opioids (any, prescription, synthetic)
- Cocaine
- Heroin

The Jupyter notebook (`Data9.ipynb`) includes:
- Data loading and cleaning
- Basic statistical analysis
- Data visualizations (including yearly distribution pie chart)
- Trend analysis

## 📂 Dataset
**File:** `drug-overdose-death-rates-new.csv`  
**Source:** [CDC WONDER](https://wonder.cdc.gov/) (Centers for Disease Control and Prevention)

### Dataset Columns
| Column Name | Description |
|-------------|-------------|
| Entity | Country (United States) |
| Code | Country code (USA) |
| Year | 1999–2020 |
| Any opioid death rates | Deaths per 100,000 (CDC WONDER) |
| Cocaine overdose death rates | Deaths per 100,000 |
| Heroin overdose death rates | Deaths per 100,000 |
| Synthetic opioids death rates | Deaths per 100,000 |
| Prescription Opioids death rates | Deaths per 100,000 |

## 🔍 Key Insights
### Yearly Distribution
![Pie Chart](https://via.placeholder.com/400?text=Yearly+Distribution+Pie+Chart)  
*(Preview of the proportion of data entries per year)*

### Statistical Summary
Key statistics generated using Pandas `describe()`:
- Mean death rates
- Minimum/maximum values
- Standard deviation
- Quartile distributions

*(Expandable with trends/peaks in specific drug categories)*

## 🛠️ Setup & Usage
### Prerequisites
- Python 3.8+
- Required libraries: `pandas`, `matplotlib`, `jupyter`

