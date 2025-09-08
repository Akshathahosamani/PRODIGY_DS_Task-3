# Prodigy InfoTech Data Science Internship Task 3

<br>  
<img src="https://github.com/Akshathahosamani/PRODIGY_DS_Task-3/blob/main/DS-3.png">  

Welcome to my submission for **Task 3** of the Data Science Internship at **Prodigy Infotech**.  
In this task, I built a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their **demographic and behavioral data** using the **Bank Marketing dataset**.  

---

## 📌 Problem Statement  

Businesses often use customer demographic and behavioral data to predict purchasing decisions. The objective of this task is to create a **classification model** that can predict whether a customer will subscribe to a product or service. This helps organizations make better marketing decisions, optimize campaigns, and improve conversion rates.  

---

## 📊 Dataset  

The dataset used is the **Bank Marketing Dataset**, available from the UCI Machine Learning Repository. It contains data related to direct marketing campaigns (phone calls) of a Portuguese banking institution.  

👉 [Sample Dataset](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203)  

### Features:  
- **Demographics:** `age`, `job`, `marital`, `education`  
- **Financial/Behavioral:** `default`, `housing`, `loan`  
- **Campaign-related:** `contact`, `month`, `day_of_week`, `duration`, `campaign`  
- **Other attributes:** `pdays`, `previous`, `poutcome`, `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed`  

**Target Variable:** `y` (binary: `"yes"` if the client subscribed, `"no"` otherwise)  

---

## 🛠 Tools and Libraries Used  

The project was carried out in **Python** using **Jupyter Notebook**. The following libraries were used:  

* **Pandas & NumPy** → Data preprocessing and manipulation  
* **Scikit-learn** → Model building, training, evaluation, and decision tree visualization  
* **Matplotlib & Seaborn** → Data visualization and plots  
* **Jupyter Notebook** → Interactive coding and documentation  

---

## 🔎 Approach  

1. **Data Preprocessing**  
   * Loaded dataset using Pandas  
   * Encoded categorical variables into numeric format using `LabelEncoder`  
   * Split data into training and testing sets  

2. **Model Training**  
   * Implemented a **Decision Tree Classifier** with `criterion="entropy"` and `max_depth=5`  
   * Trained the model using training data  

3. **Model Evaluation**  
   * Evaluated model using Accuracy, Precision, Recall, and F1-score  
   * Plotted a **Confusion Matrix Heatmap**  
   * Visualized the **Decision Tree** structure to interpret decision rules  

---

## 📈 Results  

* **Model Accuracy:** ~85–90% (may vary with random states)  
* **Important Features:** Call duration, number of contacts, and employment variation rate significantly influenced predictions  
* The decision tree visualization clearly shows rules that lead to customer subscription predictions  

---

## ✅ Conclusion  

This task demonstrates how **Decision Trees** can be applied to predict customer purchasing behavior in marketing campaigns. By analyzing customer demographics, past campaign outcomes, and economic indicators, we can build interpretable models that help businesses optimize their strategies and improve campaign effectiveness.  

---

👩‍💻 **Developed by:** Akshatha Hosamani  
📅 Internship: Prodigy InfoTech – Data Science  
