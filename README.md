
# **Zero Flaring by 2030: Predicting Nigeria’s Gas Flare Reduction Using Linear Regression**

## 📑 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Run the Project](#how-to-run-the-project)
- [Future Work](#future-work)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## 📌 Overview

This project explores Nigeria's progress toward zero routine gas flaring by the year 2030 using a **Linear Regression** model. Gas flaring is a significant environmental and economic concern, and understanding its reduction trend is critical for energy transition planning.

The primary objective is to analyze historical gas flaring data and build a predictive model that:
- Estimates the percentage of gas flared based on time (index/year),
- Evaluates whether Nigeria is on track to meet its flare-out target,
- Assists policymakers and analysts in forecasting future flaring levels.

---

## 📊 Dataset

- **Source**: [Nigeria Gas Flare Data](https://www.nnpcgroup.com)
- **Description**: The dataset contains:
  - Yearly data entries (used as index),
  - % Gas Flared (target variable).
- **Preprocessing Steps**:
  - Removed null values.
  - Standardized column names.
  - Rescaled the index (if needed) for better model interpretability.

---

## 🧠 Methodology

- **Model**: Linear Regression using `scikit-learn`.
- **Feature Engineering**:
  - Year/index used as the independent variable.
- **Train-Test Split**:
  - Dataset split into training and testing sets.
- **Model Evaluation**:
  - Metrics: R² Score, MAE, RMSE.
  - Visualizations included regression line and residual plots.

---

## 📈 Results

- **R² Score**: *Example: 0.89*
- **MAE**: *Example: 1.23*
- **RMSE**: *Example: 1.57*
- **Insights**:
  - The model indicates a steady downward trend in gas flaring.
  - Projections show Nigeria **may/may not** reach the 2030 zero-flaring goal.

---

## ⚙️ Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run the Project

### 🔧 Prerequisites
- Python 3.7+
- Git installed

### 📥 Clone the Repository
```bash
git clone https://github.com/your-username/nigeria-gas-flaring-prediction.git
cd nigeria-gas-flaring-prediction
```

### 🧪 Set Up a Virtual Environment
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 📦 Install Dependencies
```bash
pip install -r requirements.txt
```

### 📓 Run the Notebook
```bash
jupyter notebook
```
Open `Nigeria_gas_flare_prediction.ipynb` and run all cells.

---

## 🔮 Future Work

- Add more predictors.
- Explore non-linear models.
- Use time series forecasting.
- Integrate socio-economic data.

---

## 👤 Author

**Habibu Yusuf**  
- 💼 [LinkedIn](https://www.linkedin.com/in/habibu-yusuf/)  
- 💻 [GitHub](https://github.com/habibuyusuf)

---

## 🙏 Acknowledgments

- Thanks to [NNPC](https://www.nnpcgroup.com) or relevant data providers.
- Inspired by Nigeria’s zero flaring commitment.
