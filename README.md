# Netflix Stock Price Prediction

---

## Overview

This project focuses on predicting Netflix (NFLX) stock prices using historical market data. By applying various machine learning regression techniques, the project aims to model stock price trends based on features such as Open, High, Low, and Volume. The target audience includes data science practitioners, financial analysts, and developers interested in time-series analysis and stock market prediction modeling.

---

## Features

* **Data Exploration**: Comprehensive analysis of historical Netflix stock data.
* **Feature Engineering**: Utilizing Open, High, Low, and Volume metrics to predict closing prices.
* **Regression Modeling**: Implementation and evaluation of multiple machine learning models:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor


* **Data Visualization**: Correlation and trend visualization using Seaborn and Matplotlib.

---

## Tech Stack

| Category | Technology |
| --- | --- |
| **Language** | Python |
| **Development** | Jupyter Notebook |
| **Data Analysis** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn, XGBoost |
| **Visualization** | Matplotlib, Seaborn |

---

## Project Structure

```text
.
├── .ipynb_checkpoints/    # Jupyter notebook checkpoints
├── NFLX.csv               # Historical Netflix stock data
├── Test-checkpoint.ipynb  # Notebook checkpoint
└── Working.ipynb          # Main notebook with analysis and modeling

```

---

## Getting Started

### Prerequisites

* Python 3.x
* Jupyter Notebook
* Required libraries:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost

```



### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd netflix-stock-price-prediction

```


2. Open the `Working.ipynb` file in your Jupyter environment.

---

## Usage

The `Working.ipynb` notebook provides the end-to-end workflow:

1. Load the `NFLX.csv` dataset.
2. Inspect data structure and verify for missing values.
3. Split the data into training and testing sets.
4. Train and test the models listed in the **Features** section to predict the 'Close' price.

---

## Data

The dataset (`NFLX.csv`) contains daily stock records with the following columns:

* **Date**: The trading date.
* **Open**: Stock price at market open.
* **High**: Highest stock price during the day.
* **Low**: Lowest stock price during the day.
* **Close**: Stock price at market close.
* **Adj Close**: Adjusted closing price.
* **Volume**: Number of shares traded.

---

## Contributing

Contributions are welcome. Please fork this repository, create a branch, and submit a pull request for any improvements or bug fixes.

---

## License

This project is licensed under the MIT License.

---

## Author

**Arnav Maheshwari**

---

## Acknowledgements

* [Scikit-Learn](https://scikit-learn.org/)
* [XGBoost](https://xgboost.readthedocs.io/)
* [Pandas](https://pandas.pydata.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
