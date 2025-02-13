# 📊 Binary Classification with Bank Churn Prediction

## 📝 Introduction  
Customer churn is a major concern in the banking sector. Retaining customers is crucial for business growth, and understanding the factors leading to churn can help in designing better customer retention strategies. This project aims to predict whether a customer will **churn (leave the bank) or stay** based on demographic, financial, and account activity data.

## 🎯 Project Aim  
The objective of this project is to **build a machine learning model** that accurately predicts customer churn. By analyzing features such as **credit score, account balance, number of products, and customer activity**, we aim to uncover **key insights** that influence a customer’s decision to leave or stay with the bank.

## 📂 Dataset Description  
The dataset consists of customer details, including **demographic information, financial status, and banking activity**. The target variable is **Exited**, where:  
- `1` ❌ → Customer **churned** (left the bank)  
- `0` ✅ → Customer **retained** (remained with the bank)  

### 🏷 Data Fields  
- **id** 🔢 – Unique identifier for each record  
- **CustomerId** 🆔 – Unique ID assigned to each customer  
- **Surname** 👤 – Customer's last name  
- **CreditScore** 📈 – Credit score (higher is better)  
- **Geography** 🌍 – Country of residence (France, Spain, Germany)  
- **Gender** 🚻 – Customer's gender (Male/Female)  
- **Age** 🎂 – Customer’s age  
- **Tenure** 📅 – Number of years the customer has been with the bank  
- **Balance** 💰 – Account balance  
- **NumOfProducts** 🛍 – Number of bank products used  
- **HasCrCard** 💳 – Whether the customer owns a credit card (`1 = Yes`, `0 = No`)  
- **IsActiveMember** ✅ – Whether the customer is an active bank member (`1 = Yes`, `0 = No`)  
- **EstimatedSalary** 💵 – Estimated annual salary of the customer  
- **Exited** ❌ – **Target variable** (`1 = Churned`, `0 = Stayed`)  

---

## 🏁 Model Performance & Results  

We trained multiple machine learning models and a deep learning model to predict customer churn. The models were evaluated using **accuracy scores**, and the results are summarized below.  

### 📊 Machine Learning Model Performance:  
| Model | Accuracy Score |
|-----------------------------|--------------|
| **Gradient Boosting Classifier** 🌟 | **0.8664** (Best Model) |
| **Random Forest Classifier** 🌲 | 0.8583 |
| **Bernoulli Naïve Bayes** 📊 | 0.8033 |
| **Decision Tree Classifier** 🌿 | 0.7959 |
| **Gaussian Naïve Bayes** 📈 | 0.7953 |
| **Logistic Regression** 🔢 | 0.7881 |
| **K-Nearest Neighbors** 📍 | 0.7596 |

The **Gradient Boosting Classifier** performed the best, making it the **most effective model** for predicting customer churn. **Random Forest** was also a strong contender, showcasing the power of **ensemble learning**.

### 🤖 Deep Learning Model Performance:  
A **deep learning model** was also trained to identify **complex patterns** in the data. While it performed well, it did not outperform **Gradient Boosting**, suggesting that **ensemble models were better suited** for this dataset.

---

## 📌 Key Takeaways  
✅ **Gradient Boosting Classifier** achieved the highest accuracy.  
✅ **Ensemble methods (Gradient Boosting & Random Forest)** outperformed traditional models.  
✅ **Naïve Bayes models** provided reasonable results but were not the best performers.  
✅ **Deep Learning captured patterns well**, but ensemble methods were superior in this case.  

### 🚀 Future Improvements  
🔹 Fine-tune **deep learning architectures** for better performance.  
🔹 Experiment with **hyperparameter tuning** for all models.  
🔹 Use **cross-validation** for a more robust evaluation.  
🔹 Try advanced ensemble methods like **XGBoost** and **LightGBM**.  

**Based on our findings, Gradient Boosting is the best model for deployment!** 🎯🔥  

---

## 📜 Kaggle Notebook  
For detailed implementation, check out the original Kaggle Notebook:  
🔗 [Binary Classification with Bank Churn Prediction](https://www.kaggle.com/code/senasudemir/binary-classifaction-with-a-bank-churn?scriptVersionId=222419493)  

---

🚀 **Thank you for exploring this project!** If you found this helpful, feel free to ⭐ star the repository!  
