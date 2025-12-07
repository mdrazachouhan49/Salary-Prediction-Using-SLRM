# Salary Prediction Using Linear Regression  
A data-driven regression model to estimate salary based on years of professional experience.

##  Overview
This project implements a **Simple Linear Regression** model to analyze the relationship between **Years of Experience** and **Salary** using Python's data science ecosystem. Through exploratory data analysis, visualization, and predictive modeling, the workflow demonstrates how machine learning can quantify experience-driven salary scaling.

The analysis includes:
- Data exploration  
- Statistical summary  
- Visual insights  
- Correlation study  
- Linear regression modeling  
- Model accuracy evaluation  
- Future salary prediction  

---

##  Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| **Python 3.11.13 | Programming environment |
| **NumPy** | Numerical computation |
| **Pandas** | Data loading & manipulation |
| **Matplotlib** | Data visualization |
| **Scikit-learn** | Linear Regression, metrics |
| **Jupyter Notebook** | Interactive development |

---

##  Project Structure

```
.
├── Salary_Prediction_Using_SLRM.ipynb          # Main notebook
├── Salary_dataset.csv                          # Input dataset
├── README.md                                   # Documentation
├── requirements.txt                            # Python dependencies
├── .gitignore                                  # Ignored files
└── LICENSE                                     # MIT License (optional)
```

---

## Exploratory Data Analysis (EDA)

Key steps include:
- Dataset overview (`info()`, `describe()`)
- Feature distribution study
- Bar charts for value counts
- Salary and experience comparison
- Histogram visualization for salary spread
- Scatter plot to observe linear relationship

The scatter plot confirms a **strong positive correlation** between experience and salary.

---

##  Regression Model

The model uses:
```python
from sklearn.linear_model import LinearRegression
```

Workflow:
1. Define features (X = YearsExperience) and target (Y = Salary)
2. Fit model using `model.fit(X, Y)`
3. Generate predictions:  
   ```python
   y_pred = model.predict(X)
   ```

---

##  Model Evaluation

Metrics calculated:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score (Coefficient of Determination)**  
- Overall **Model Accuracy** derived from R²

These metrics validate that the linear model provides an excellent fit for this dataset.

---

##  Salary Prediction

Using the regression equation:

```
Salary = B0 + B1 * (Years of Experience)
```

The model predicts salary for a given input such as **10.6 years of experience**, producing a realistic salary estimate in INR.

---

##  How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Salary_Prediction_Using_SLRM.ipynb
   ```

---

##  License

This project is distributed under the **MIT License**, allowing reuse and modification for educational and analytical purposes.

---

##  Author

**Md. Raza Chouhan**  
GitHub: https://github.com/mdrazachouhan49

---







