# 📈 Tesla Stock Price Prediction Using Machine Learning

## 📌 About
A machine learning model that predicts Tesla stock price 
movement (up or down) based on historical stock data 
from 2010, using classification algorithms.

## 🛠️ Tools & Technologies
- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Seaborn
- Matplotlib

## 🤖 Models Used
- Logistic Regression
- Support Vector Machine (SVC)
- XGBoost Classifier

## 📊 Results
| Model | Validation Accuracy |
|-------|-------------------|
| XGBoost | 57.3% |
| Logistic Regression | 54.4% |
| SVC | 44.7% |

✅ Best Model: **XGBoost Classifier**

## 🔄 Process
1. Loaded 1692 Tesla stock records
2. Feature engineering (open-close, low-high, quarter-end)
3. Data visualization and correlation analysis
4. Model training and comparison
5. Confusion matrix evaluation

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Add Tesla.csv dataset to the project folder
4. Run the notebook:
   tesla_stock_prediction.ipynb
