# 📊 Spread Locator: Statistical Distribution Analysis Model

## 📌 Project Overview

This project analyses e-commerce transaction data using statistical
distribution modelling and transformation techniques.

The objective is to determine which statistical distribution best fits
transaction amounts and derive insights for decision-making.

------------------------------------------------------------------------

## 📂 Project Structure

    Spread-Locator/
    │
    ├── spread_locator_dataset.csv
    ├── Spread_Locator_Project_GitHub_Ready.ipynb
    └── README.md

------------------------------------------------------------------------

## 🗂 Dataset Description

The dataset contains 1000 transaction records like:

-   Transaction ID
-   Customer ID
-   Transaction Amount (₹)
-   Transaction Date
-   Transaction Count (weekly)
-   Region
-   Transaction Status (Success/Fail)

------------------------------------------------------------------------

## 📈 Statistical Methods Used

-   Bernoulli Distribution (Transaction Success)
-   Poisson Distribution (Transaction Count)
-   Log-Normal Distribution Modelling
-   Q-Q Plot for Normality Testing
-   Box-Cox Transformation
-   Z-Score Probability Calculation
-   PDF and CDF Visualisation

------------------------------------------------------------------------

## 📊 Key Findings

-   Transaction amounts are right-skewed.
-   Log-Normal distribution better models transaction data.
-   Box-Cox transformation reduces skewness.
-   Probability analysis helps identify high-value transaction
    likelihood.

------------------------------------------------------------------------

## ▶ How to Run

1.  Install required libraries:

```{=html}
<!-- -->
```
    pip install pandas numpy matplotlib scipy

2.  Open Jupyter Notebook:

```{=html}
<!-- -->
```
    jupyter notebook

3.  Run all cells in `Spread_Locator.ipynb`

------------------------------------------------------------------------

## 🛠 Tools Used

-   Python
-   Pandas
-   NumPy
-   SciPy
-   Matplotlib
-   Jupyter Notebook

------------------------------------------------------------------------

## 📎 Academic Note

This project demonstrates practical application of statistical
distribution modeling, spread analysis, transformation techniques, and
probability concepts in real-world transaction data.
