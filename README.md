# Tech Layoffs Analysis and Forecast (2022–2025)

This repository presents an in-depth analysis of global tech layoffs from 2022 through 2025. Using data from Layoffs.fyi, the project identifies workforce trends, analyzes the most affected sectors and companies, and forecasts future layoffs using time series modeling techniques.

## Dataset

- **Source:** [Layoffs.fyi](https://layoffs.fyi/)
- **Format:** CSV
- **Coverage:** 2022 to 2025
- **Key Columns:** Company, Date, Location, Number Laid Off, Percentage Laid Off, Industry, Country, Stage, Capital Raised

## Data Preparation

- Cleaned and standardized column formats (dates, percentages, and currency)
- Filtered for layoff events occurring between 2022 and 2025
- Handled missing data and outliers
- Aggregated layoffs on a monthly basis for time series analysis

## Exploratory Data Analysis (EDA)

The analysis explores:

- Year-over-year layoff trends
- Monthly layoff activity across the tech sector
- Industries and funding stages most affected
- Top companies by total layoffs
- Country-level distributions of layoffs

## Forecasting Approach

### ARIMA Model (Backtesting for 2024)
- Trained on data through 2023
- Forecasted monthly layoffs for 2024
- Compared forecast to actuals for model evaluation
- Metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)

### Prophet Model (Forecast for 2025)
- Used Prophet to capture trend and seasonality
- Forecasted monthly layoffs for 2025
- Produced component plots for interpretability
- Estimated total layoffs for the full year

## Visualizations

This project includes a range of visual outputs to support findings, including:

- Total layoffs per year
- Monthly layoffs over time
- Top 10 companies by layoffs
- Industry and country breakdowns

All visuals are stored in the `/charts` directory.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Statsmodels
- Prophet

## Project Structure

 - data/ # Raw and processed datasets
 - charts/ # Generated visualizations
 - notebooks/ # Jupyter notebooks for EDA and forecasting
 - report.pdf # Final report summarizing findings
 - README.md # Project documentation
 - layoffs_forecast.ipynb # Core notebook with analysis and modeling
 - Tech Layoffs 2022-2025.pbix #Interactive Dashboard with forecast analysis and global map

## Contact
**Author:** Wesley Hilton  
**LinkedIn:**  https://www.linkedin.com/in/wesleyhilton/ 
