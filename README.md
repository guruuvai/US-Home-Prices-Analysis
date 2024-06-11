# US-Home-Prices-Analysis
Analysis of Factors Influencing US Housing Prices Over the Last 20 Years
![Data Collection   Analysis Educational Presentation in Pink and Blue Lined Style](https://github.com/guruuvai/US-Home-Prices-Analysis/assets/67874401/832163f8-c687-47e8-95e8-f4bf1d365b41)

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
- ![image](https://github.com/guruuvai/US-Home-Prices-Analysis/assets/67874401/e3c2bd8e-93fc-43a6-9808-ff82b5186b2e)

![image](https://github.com/guruuvai/US-Home-Prices-Analysis/assets/67874401/cd5d9a29-9c70-458d-9935-5241267c2ef7)

![image](https://github.com/guruuvai/US-Home-Prices-Analysis/assets/67874401/a0b33cdd-1239-43dd-81b5-9d3d1a15bd10)

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

## Analysis and Model

### Regression Model
An Ordinary Least Squares (OLS) regression model was used to analyze the impact of the selected factors on median home prices.
#### Regression Results

| Variable            | Coefficient   | Std. Error | t-Statistic | P-value  | 95% Confidence Interval |
|---------------------|---------------|------------|-------------|----------|-------------------------|
| Intercept           | -770,900.0    | 328,000.0  | -2.353      | 0.022    | [-1.42e+06, -1.17e+05]  |
| Mortgage Rates      | 2,273.1       | 2,245.5    | 1.012       | 0.315    | [-2211.453, 6757.705]   |
| Household Inventory | 8.3           | 3.2        | 2.577       | 0.012    | [1.866, 14.719]         |
| GDP                 | 4.5           | 5.1        | 0.883       | 0.380    | [-5.730, 14.817]        |
| Unemployment Rate   | -2,900.1      | 1,044.7    | -2.776      | 0.007    | [-4986.508, -813.622]   |
| Population Growth   | -5,425.5      | 9,871.8    | -0.550      | 0.584    | [-2.51e+04, 1.43e+04]   |
| Building Permits    | 46.1          | 7.3        | 6.287       | 0.000    | [31.487, 60.804]        |
| Median HH Income    | -2.7          | 0.6        | -4.257      | 0.000    | [-3.985, -1.440]        |

**Notes:**
1. Standard Errors assume that the covariance matrix of the errors is correctly specified.
2. The condition number is large (4.75e+07), which might indicate strong multicollinearity or other numerical problems.

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
For any questions or discussions, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/vaibhavtembhekar/)

