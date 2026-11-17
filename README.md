# World Happiness Report 2019: Exploratory Data Analysis

Exploratory data analysis of the World Happiness Report 2019 (156 countries) to understand which factors are associated with national happiness, and which countries do not fit the pattern.

## Tools
Python · pandas · NumPy · Matplotlib · Seaborn · Jupyter

## Questions
- How is happiness distributed across countries?
- Which countries are the happiest and the least happy?
- Which factors are most strongly associated with happiness?
- Which countries are happier or less happy than their GDP predicts?

## Key Findings
- **GDP per capita (r = 0.79), social support (r = 0.78) and healthy life expectancy (r = 0.78)** are the strongest correlates of happiness. Generosity shows almost no relationship (r = 0.08).
- **Money is not everything:** countries with similar GDP can differ hugely in happiness. Costa Rica and Botswana have almost the same GDP, but scores of 7.17 vs 3.49.
- **Latin America** (Costa Rica, Guatemala, Nicaragua) is happier than GDP predicts, while **the Middle East** (Syria, Iran, Iraq, Egypt) is less happy than GDP predicts.
- **Data quality:** Somalia has GDP = 0.000, which is likely missing data.

*These are correlations, not causal effects.*

## Data
[World Happiness Report 2019 on Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness)

## How to run
Open `world_happiness_eda.ipynb` in Jupyter Notebook and run all cells.
