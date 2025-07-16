# MLE Econometrics Notebook

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Econometrics](https://img.shields.io/badge/Econometrics-MLE%20%7C%20OLS-red.svg)](https://en.wikipedia.org/wiki/Econometrics)
[![Stats](https://img.shields.io/badge/Statistics-Robust%20SE%20%7C%20Heteroscedasticity-purple.svg)](https://en.wikipedia.org/wiki/Robust_standard_error)
[![Notebooks](https://img.shields.io/badge/Notebooks-7%20Files-brightgreen.svg)](https://jupyter.org/)
[![Dependencies](https://img.shields.io/badge/Dependencies-7%20Packages-yellow.svg)](https://pypi.org/)

Welcome to the **MLE Econometrics Notebook** repository! This project contains a series of Python notebooks that demonstrate econometric techniques using Maximum Likelihood Estimation (MLE) and Ordinary Least Squares (OLS), with a focus on robust standard error calculations and heteroscedasticity tests.

## Repository Overview

This repository is a collection of Jupyter notebooks designed to provide clear and practical examples of key econometric concepts, implemented in Python. 

## Table of Contents

### Notebooks
1. **[MLE Linear Model in Python](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_linear_model_python.ipynb)**  
   Implements a linear regression model using Maximum Likelihood Estimation (MLE). Includes comprehensive model diagnostics and visualizations.

2. **[OLS Linear Model in Python](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/OLS_linear_model_Python.ipynb)**  
   Demonstrates a traditional Ordinary Least Squares (OLS) regression with diagnostics and visualizations.

3. **[HC0 Robust Standard Errors](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_HC0_Python.ipynb)**  
   Calculates robust standard errors (HC0) to account for heteroscedasticity in residuals.

4. **[HC1 Robust Standard Errors](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_HC1_Python.ipynb)**  
   Implements HC1 robust standard errors with finite-sample corrections for smaller datasets.

5. **[HC2 Robust Standard Errors](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_HC2_Python.ipynb)**  
   Includes leverage adjustments for residuals using HC2 robust standard errors.

6. **[HC3 Robust Standard Errors](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_HC3_Python.ipynb)**  
   Features a stricter leverage adjustment approach with HC3 robust standard errors for high-leverage observations.

7. **[White Test for Heteroscedasticity](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main/blob/main/MLE_White_test_python.ipynb)**  
   Conducts a White Test to detect heteroscedasticity in regression residuals.

---

## Features

- Implementation of **Maximum Likelihood Estimation (MLE)** and **Ordinary Least Squares (OLS)** techniques.
- Robust standard errors using HC0, HC1, HC2, and HC3 corrections.
- Statistical diagnostics including residual analysis, \(R^2\), \(t\)-tests, \(F\)-tests, and more.
- Heteroscedasticity detection using the **White Test**.
- Comprehensive explanations and visualizations to enhance understanding.

---

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or Jupyter Lab
- Required Python packages:
  - `numpy`
  - `scipy`
  - `pandas`
  - `statsmodels`
  - `matplotlib`
  - `seaborn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/simonpierreboucher02/mle_econometrics_notebook-main.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd mle_econometrics_notebook-main
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

---

## Usage

Each notebook is self-contained and includes examples with detailed explanations and outputs. Simply open the desired notebook in Jupyter Notebook or Jupyter Lab and follow along.

---

## Author

This repository is maintained by **Simon-Pierre Boucher**. Feel free to reach out or contribute to the project if you have suggestions or improvements!

---

## Repository URL

[https://github.com/simonpierreboucher02/mle_econometrics_notebook-main](https://github.com/simonpierreboucher02/mle_econometrics_notebook-main)

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

