# Austo Automobiles â€” Exploratory Data Analysis

Exploratory data analysis of Austo Motor Company's customer and sales data, supporting a business case for expanding operations from the UK into the US market.

## Business context

Austo Motor Company wants to understand who its car buyers are and what drives their purchases before expanding into a new market. This analysis explores customer demographics, income, and vehicle segment preferences to surface patterns that can inform market entry and segmentation strategy.

## Dataset

- **1,581 records, 14 columns**, no missing values
- Customer attributes: `Age`, `Gender`, `Profession`, `Marital_status`, `Education`, `No_of_Dependents`, `Personal_loan`, `House_loan`, `Partner_working`
- Financial attributes: `Salary`, `Partner_salary`, `Total_salary`
- Purchase attributes: `Price`, `Make` (vehicle segment: Hatchback, Sedan, SUV)

## Approach

The notebook (`EDA_Naresh_Peta_Austo_automobile.html`) walks through:

1. **Data understanding & cleaning** â€” structure, types, and missing-value checks
2. **Univariate analysis** â€” distributions of age, income, and segment counts
3. **Bivariate analysis** â€” relationships between income, price, and vehicle segment
4. **Insights & interpretation** â€” translating patterns into business takeaways

## Key findings

| Segment | Volume | Avg. Price | Avg. Household Income |
|---|---:|---:|---:|
| Hatchback | 884 | 25,561 | 72,676 |
| Sedan | 460 | 42,672 | 82,241 |
| SUV | 237 | 59,304 | 99,316 |

- Household income (`Total_salary`) correlates with price at **r = 0.35**; individual salary alone at **r = 0.39** â€” income is a meaningful but not sole driver of purchase price.
- Hatchbacks are the highest-volume segment, while SUVs skew toward the highest-income households.
- Younger professionals make up the largest share of buyers.

## Recommendation

These patterns point to a segmented go-to-market approach â€” value-focused positioning for hatchbacks aimed at younger, salaried professionals, and premium positioning for SUVs targeted at higher-income, dual-income households.

## Tools

Python, pandas, matplotlib/seaborn (Jupyter notebook, exported to HTML)

## Viewing the analysis

Download `EDA_Naresh_Peta_Austo_automobile.html` and open it in a browser to view the full notebook with code, charts, and outputs.
