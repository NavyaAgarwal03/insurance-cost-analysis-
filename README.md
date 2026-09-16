
# 🏥 Insurance Cost Analysis & Prediction (Machine Learning)

## 📌 Project Overview

This project analyzes a medical insurance dataset to identify key factors affecting insurance charges and builds a machine learning model to predict costs.

The goal is to combine **data analysis + business insights + predictive modeling** to understand how features like age, BMI, and smoking habits influence insurance pricing.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) to uncover patterns
* Identify key drivers of insurance costs
* Build a regression model to predict medical charges
* Derive business insights for insurance pricing strategies

---

## 📂 Dataset Description

The dataset contains the following features:

* **age** → Age of the individual
* **sex** → Gender
* **bmi** → Body Mass Index
* **children** → Number of dependents
* **smoker** → Smoking status (yes/no)
* **region** → Residential area
* **charges** → Medical insurance cost (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)

Key analysis performed:

* Distribution of insurance charges
* Impact of smoking on cost
* Relationship between age, BMI, and charges
* Correlation between variables

### 📊 Key Insights

* Smokers have significantly higher insurance charges than non-smokers
* Age shows a positive correlation with medical expenses
* BMI moderately impacts insurance costs
* Region has minimal effect on pricing

---

## 🧹 Data Preprocessing

* Handled categorical variables using **one-hot encoding**
* Split dataset into training and testing sets (80/20 split)

---

## 🤖 Model Building

### Model Used:

* Linear Regression

### Steps:

* Trained model on training data
* Predicted charges on test data
* Evaluated performance using metrics

---

## 📈 Model Evaluation

* **Mean Absolute Error (MAE):** Measures average prediction error
* **R² Score:** Indicates how well the model explains variance

The model provides a reasonable baseline for predicting insurance costs.

---

## 💼 Business Impact

This analysis can help insurance companies:

* Design better pricing strategies
* Identify high-risk individuals
* Encourage healthier lifestyle choices
* Improve cost prediction accuracy

---

## 🛠️ Tech Stack

* Programming Language: Python
* Libraries:

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn

---

## 📁 Project Structure

```
insurance-cost-prediction-ml/
│
├── insurance.csv
├── insurance_analysis.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/insurance-cost-prediction-ml.git
```

2. Navigate to the folder:

```
cd insurance-cost-prediction-ml
```

3. Create virtual environment:

```
python3 -m venv .env
source .env/bin/activate   # Mac
```

4. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

5. Run the notebook:

* Open `insurance_analysis.ipynb` in Jupyter/VS Code

---

## ⭐ Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a web app using Streamlit
* Add more real-world datasets

---

## 🙌 Author

**Navya Agarwal**
Bioengineering Graduate | Aspiring Business/Data Analyst

---

## 📬 Feedback

If you have suggestions or feedback, feel free to connect or open an issue!
