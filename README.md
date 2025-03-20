# Credit Risk Analysis

This project analyzes credit default risks using Home Credit datasets from Kaggle. I explored factors like loan type, gender, family size, and past applications to identify patterns in defaults (TARGET=1) vs. repayments (TARGET=0).

## Key Features
- **Data**: `application_data.csv` (307k rows) and `previous_application.csv` (1.6M rows).
- **Cleaning**: Removed columns with >40% missing values and merged datasets.
- **Visuals**: 11 plots (barplots, heatmaps, boxplots, scatter, etc.).
- **Findings**: Identified risky clients (e.g., large families) and safe candidates (e.g., revolving loans).

## How to Run
1. Clone this repository: `git clone https://github.com/MykytaSalykin/Credit-Risk-Analysis.git`.
2. Open `Credit Risk Analysis.ipynb` in Google Colab.
3. Upload datasets from [Kaggle Home Credit](https://www.kaggle.com/c/home-credit-default-risk/data).
4. Run all cells.

## Tools
- Python, Pandas, Seaborn, Matplotlib

## Next Steps
- Add predictive modeling (e.g., logistic regression).
- Explore more variables like credit history.

## Author
- Mykyta Salykin
