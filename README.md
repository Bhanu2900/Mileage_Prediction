# 🚗 Mileage Prediction using Machine Learning

This project aims to predict a car's fuel efficiency (measured in miles per gallon - MPG) using various vehicle attributes. It is a supervised regression task implemented using Python and Scikit-learn.

---

## 📌 Use Case

Predicting car mileage is important for:
- Automotive manufacturers optimizing fuel efficiency.
- Buyers comparing cars based on performance.
- Regulatory agencies tracking environmental impact.

This ML model uses features like engine size, horsepower, weight, and origin to make accurate mileage predictions.

---

## 📂 Project Structure

```
mileage-prediction/
│
├── project_2.ipynb           # Jupyter notebook version
├── mileage_prediction.py     # Python script version of the project
├── requirements.txt          # List of Python dependencies
├── .gitignore                # Git ignore rules
└── README.md                 # Project documentation
```

---

## 🧠 Model Details

- **Type**: Regression
- **Algorithm**: Linear Regression (can be extended to Random Forest, XGBoost)
- **Libraries Used**:
  - pandas, numpy
  - matplotlib, seaborn
  - scikit-learn

---

## 📊 Dataset Overview

The dataset contains the following features:

- `Cylinders`
- `Displacement`
- `Horsepower`
- `Weight`
- `Acceleration`
- `Model Year`
- `Origin`
- `MPG` (target variable)

---

## 🔧 How to Run

### Option 1: Run Jupyter Notebook

```bash
jupyter notebook project_2.ipynb
```

### Option 2: Run Python Script

```bash
python mileage_prediction.py
```

---

## 📦 Install Dependencies

Install required packages using:

```bash
pip install -r requirements.txt
```

---

## ✅ Output Example

The model gives a predicted MPG value for a given set of input features and displays metrics like MAE, MSE, and R² score.

---

## 💡 Improvements

- Use hyperparameter tuning (GridSearchCV)
- Try advanced regression models (e.g., Gradient Boosting)
- Visualize feature importance

---

## 👨‍💻 Author

**Bhanu Pratap**  
B.Tech AI & DS    
GitHub: [Bhanu2900](https://github.com/Bhanu2900)

---

## 📝 License

This project is open-source and available under the MIT License.
