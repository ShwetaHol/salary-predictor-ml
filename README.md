# Salary Predictor — Linear Regression

## Overview
End to end machine learning project predicting
salary based on years of experience using
Linear Regression.

## Results
| Metric | Score      |
|--------|------------|
| R²     | 0.89       |
| MAE    | $6,692.36  |
| RMSE   | $7,467.38  |

## Tech Stack
- Python 3.13
- pandas
- scikit-learn
- matplotlib
- joblib
- Jupyter Notebook

## Project Structure
```
Projects/
├── salary_predictor.ipynb  ← full notebook
├── Salary_Data.csv         ← dataset
├── salary_model.pkl        ← saved model
└── README.md
```

## What I built
- Explored and visualised real salary data
- Built Linear Regression model from scratch
- Evaluated using MAE, RMSE and R² metrics
- Saved trained model using joblib
- Predict salary for any years of experience

## How to run
```bash
git clone https://github.com/YOURUSERNAME/salary-predictor-ml
cd salary-predictor-ml
pip install -r requirements.txt
jupyter notebook
```

## What I would improve
- Add more features (education, location, job title)
- Try polynomial regression
- Deploy as FastAPI web app
```

---

**Step 7 — Create requirements.txt**

Create `requirements.txt` file:
```
pandas
matplotlib
scikit-learn
joblib
jupyter
ipykernel