# Credit Risk Analysis

This project analyzes credit default risks using Home Credit datasets from Kaggle. I explored factors like loan type, gender, family size, and past applications to identify patterns in defaults (TARGET=1) vs. repayments (TARGET=0).

## Key Features
- **Data**: `application_data.csv` (307k rows) and `previous_application.csv` (1.6M rows).
- **Cleaning**: Removed columns with >40% missing values and merged datasets.
- **Visuals**: 11 plots (barplots, heatmaps, boxplots, scatter, etc.).
- **Findings**: Identified risky clients (e.g., large families) and safe candidates (e.g., revolving loans).

## Visualizations
<img width="846" height="470" alt="изображение" src="https://github.com/user-attachments/assets/105ca867-fbdf-44be-8cd7-b63c327c2d9c" />
<img width="663" height="658" alt="изображение" src="https://github.com/user-attachments/assets/f8d53789-03f7-4ad0-ac3c-e78cbdef9480" />
<img width="855" height="529" alt="изображение" src="https://github.com/user-attachments/assets/396b750b-7b5a-42ec-91f8-e7b0b1b0aef4" />


## How to Run
1. Clone this repository: `git clone https://github.com/MykytaSalykin/Credit-Risk-Analysis.git`.
2. Open `Credit Risk Analysis.ipynb` in Google Colab.
3. Upload datasets from [Kaggle Home Credit](https://www.kaggle.com/c/home-credit-default-risk/data).
4. Run all cells.

## Tools
- Python, Pandas, Seaborn, Matplotlib

## Author
- Mykyta Salykin
