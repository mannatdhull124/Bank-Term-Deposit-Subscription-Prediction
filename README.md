# Bank-Term-Deposit-Subscription-Prediction
Logistic Regression model to predict customer response to bank marketing campaigns for term deposit subscription.

# Bank Term Deposit Subscription Prediction using Logistic Regression

## 📌 Project Overview

This project aims to predict whether a customer will subscribe to a bank term deposit using Machine Learning techniques, specifically **Logistic Regression**.

The dataset contains customer-related and marketing campaign information such as:

- Age
- Job
- Marital Status
- Education
- Balance
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Details
- Previous Marketing Outcomes

The objective is to help banks identify potential customers who are more likely to subscribe to a term deposit, allowing better marketing strategies and improved business decisions.

---

# 🎯 Problem Statement

Banks conduct marketing campaigns to promote term deposit subscriptions. However, contacting every customer is inefficient and costly.

The goal of this project is to build a predictive model that can determine whether a customer will subscribe to a term deposit based on customer demographics and campaign-related features.

---

# ⚙️ Solution Approach

The following steps were performed to solve the problem:

## 1. Data Preprocessing

- Handled missing values
- Cleaned dataset for modeling
- Converted categorical variables into numerical format using **One-Hot Encoding**
- Prepared features and target variable for training

---

## 2. Exploratory Data Analysis (EDA)

Performed data visualization and analysis using:

- Count plots
- Histograms
- Boxplots

Key observations:

- Certain job categories showed higher subscription rates
- Customers contacted multiple times had different conversion behavior
- Some numerical features contained outliers

---

## 3. Handling Class Imbalance

- Checked target variable distribution
- Applied balancing techniques if required to improve model performance

---

## 4. Feature Scaling

Applied **Standardization** to normalize numerical features before training the model.

---

## 5. Model Building

Implemented **Logistic Regression** model.

Logistic Regression predicts the probability of a customer subscribing to a term deposit.

---

## 6. Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- ROC Curve
- Classification Performance Metrics

The model performance was tested on unseen test data.

---

## 7. Interpretation

Analyzed model coefficients to understand feature importance.

Important factors influencing subscription included:

- Previous campaign outcome
- Contact duration
- Account balance
- Loan status
- Age

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

# 📂 Project Structure

```bash
├── Bank_Term_Deposit_Prediction.ipynb
├── bank.csv
├── README.md
```

---

# 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Prediction & Interpretation

---

# 🚀 How to Run the Project

## 1. Clone Repository

```bash
git clone <your-github-repository-link>
```

---

## 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Bank_Term_Deposit_Prediction.ipynb
```

---

# 📈 Results

The Logistic Regression model successfully predicted whether customers are likely to subscribe to a term deposit based on demographic and campaign-related information.

The project demonstrates how Machine Learning can assist banks in improving marketing efficiency and customer targeting.

---

# 🔮 Future Improvements

- Apply advanced classification algorithms
- Hyperparameter tuning
- Feature engineering improvements
- Deploy model using Flask or Streamlit
- Build interactive prediction dashboard

---

# 👨‍💻 Author

Mannat

---

# ⭐ Conclusion

This project demonstrates the complete Machine Learning workflow for customer subscription prediction using Logistic Regression, including preprocessing, visualization, model training, evaluation, and interpretation.

