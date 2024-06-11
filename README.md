# US-Home-Prices-Analysis
Analysis of Factors Influencing US Housing Prices Over the Last 20 Years

## Project Overview

This project aims to analyze the factors influencing US housing prices over the last 20 years using publicly available data. The analysis explores the impact of various economic indicators on median home prices.

## Data Sources

The datasets used in this analysis were obtained from the Federal Reserve Economic Data (FRED) website:
- Mortgage Rates: 30-Year Fixed Rate Mortgage Average in the United States
- Unemployment Rate: Unemployment Rate in the United States
- Building Permits: New Privately-Owned Housing Units Authorized in Permit-Issuing Places
- Median Household Income: Real Median Household Income in the United States
- GDP: Gross Domestic Product (GDP) of the United States
- Population Growth: Population Growth in the United States
- Housing Inventory: Total Housing Units in the United States

## Analysis and Model

### Regression Model
An Ordinary Least Squares (OLS) regression model was used to analyze the impact of the selected factors on median home prices.

#### Model Statistics
- **R-squared**: 0.973
- **Adjusted R-squared**: 0.970
- **F-statistic**: 328.9
- **Prob (F-statistic)**: 3.49e-48

#### Model Coefficients
| Factor               | Coefficient   | Std. Error | t-Statistic | P-value  |
|----------------------|---------------|------------|-------------|----------|
| Intercept            | -770,900.0    | 328,000.0  | -2.353      | 0.022    |
| Mortgage Rates       | 2,273.1       | 2,245.5    | 1.012       | 0.315    |
| Household Inventory  | 8.3           | 3.2        | 2.577       | 0.012    |
| GDP                  | 4.5           | 5.1        | 0.883       | 0.380    |
| Unemployment Rate    | -2,900.1      | 1,044.7    | -2.776      | 0.007    |
| Population Growth    | -5,425.5      | 9,871.8    | -0.550      | 0.584    |
| Building Permits     | 46.1          | 7.3        | 6.287       | 0.000    |
| Median HH Income     | -2.7          | 0.6        | -4.257      | 0.000    |

### Key Findings
- **Household Inventory** and **Building Permits** positively influence median home prices.
- **Unemployment Rate** and **Median Household Income** negatively influence median home prices.

### Practical Uses
- **Policymakers** can use these insights to understand the impact of economic policies on housing markets.
- **Real Estate Professionals** can adjust their strategies based on the factors driving housing prices.
- **Investors** can make informed decisions about real estate investments.

## Repository Structure

- `data/`: Contains the datasets used for the analysis.
- `scripts/`: Contains the Jupyter Notebook and Python scripts used for the analysis.


## Conclusion
This project provided valuable insights into the factors influencing US housing prices, enabling better decision-making in real estate and policy sectors. Feel free to explore the repository and contribute to the conversation!

Contact
For any questions or discussions, feel free to reach out to me on LinkedIn{https://www.linkedin.com/in/vaibhavtembhekar/}.
