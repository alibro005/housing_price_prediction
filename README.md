# Housing Price Prediction

A baseline machine learning project for predicting housing prices using **Linear Regression**, implemented in a Jupyter Notebook.

---

## Overview

This project builds and evaluates a linear regression model to predict residential property prices based on structured housing data. It serves as a clean, reproducible baseline for further experimentation with more advanced regression techniques.

---

## Project Structure

```
housing_price_prediction/
├── data/                  # Raw datasets
├── model/              
|    ├── housing.ipynb     # Main Jupyter Notebook (EDA, training, evaluation)
└── LICENSE                # MIT License
```

---

## Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Core Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib` / `seaborn`

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/alibro005/housing_price_prediction.git
cd housing_price_prediction
```

### 2. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open the notebook file and run all cells sequentially.

---

## Workflow

1. **Data Loading** — Load housing dataset from the `data/` directory
2. **Exploratory Data Analysis (EDA)** — Understand distributions, correlations, and missing values
3. **Preprocessing** — Handle missing data, encode features, and scale inputs
4. **Model Training** — Fit a Linear Regression model using `scikit-learn`
5. **Evaluation** — Assess performance using metrics such as RMSE and R²

---

## License

This project is licensed under the [MIT License](LICENSE).

---

*Muhammad Ali Siddiqui © 2026*
