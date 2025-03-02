# Employee Attrition Prediction - AI for Human Resources

## 📌 Project Overview
Employee turnover is a major challenge for companies, leading to high costs in hiring, onboarding, and training. This project aims to develop a predictive AI model that identifies employees at risk of leaving the company.

By leveraging historical employee data, we analyze patterns and predict potential attrition, allowing HR teams to take proactive measures to retain valuable employees.

---

## 🎯 Objectives
- Analyze employee-related data, including demographics, job satisfaction, salary, and work conditions.
- Apply Machine Learning models to predict which employees are likely to leave.
- Evaluate model performance to ensure reliable predictions.
- Provide business insights to support HR decision-making and reduce employee turnover.

---

## 🗂️ Dataset
- **Source:** The dataset contains 1,470 records with 35 features related to employee information.
- **Features include:**
  - Age, Business Travel, Department, Distance from Home, Education, Job Satisfaction, Monthly Income, Work-Life Balance, and more.
- **Target Variable:** `Attrition` (Yes/No) - whether an employee leaves the company.

---

## 🔬 Exploratory Data Analysis (EDA)
- Handled missing values and cleaned irrelevant features.
- Visualized data distributions and correlations.
- Identified key factors contributing to employee attrition.

---

## 🏗️ Machine Learning Models Used
### 1️⃣ **Logistic Regression**
- Accuracy: **91%**
- Precision for attrition class: **86%**
- Identified key factors influencing attrition.

### 2️⃣ **Random Forest Classifier**
- Accuracy: **87%**
- Precision for attrition class: **69%**
- More complex but slightly lower recall for attrition cases.

### 3️⃣ **Deep Learning (Neural Network)**
- Accuracy: **86%**
- Precision for attrition class: **55%**
- Trained using TensorFlow with multiple dense layers.

---

## 📊 Key Insights
- Employees with lower job involvement and job satisfaction were more likely to leave.
- Distance from home and monthly income also played significant roles.
- Employees with lower job levels and stock option levels had higher attrition rates.

---

## 🏆 Results and Conclusion
- The **Logistic Regression** model performed the best in terms of balanced accuracy and interpretability.
- The **Random Forest** model captured more complexity but lacked recall for attrition cases.
- The **Deep Learning** model overfitted slightly but still provided valuable insights.
- **Business Impact:** HR teams can now identify high-risk employees and take retention actions proactively.

---

## ⚙️ Technologies Used
- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn** (Data Analysis & Visualization)
- **Scikit-Learn, TensorFlow** (Machine Learning & Deep Learning)
- **Google Colab** (Model Training & Development)

---

## 🚀 Future Work
- Improve model generalization using SMOTE to balance classes.
- Implement advanced feature engineering for better insights.
- Deploy the best-performing model into an HR analytics dashboard.

---

## ✉️ Contact
If you have any questions or suggestions, feel free to reach out!

**Author:** Juan Alberto Pacheco  
📧 Email: jpachecoparedes@gmail.com 
🔗 [LinkedIn Profile](https://www.linkedin.com/in/juanpachecods)

