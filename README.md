# AllLife Bank - Personal Loan Prediction 🚀  

**Author:** Dhivya Marimuthu  
**Program:** Post Graduate Program in Artificial Intelligence and Machine Learning (Great Learning & UT Austin)

## 📌 Project Overview  
AllLife Bank aims to increase its customer base for personal loans. The bank wants to identify liability customers who are most likely to convert into loan customers. This project builds a **Decision Tree model** to predict personal loan purchases and provides business recommendations based on data-driven insights.

## 🎯 Objective  
- Predict whether a liability customer will **buy a personal loan**.  
- Identify the **most influential customer attributes** affecting loan purchases.  
- Provide **actionable insights** for targeted marketing strategies.  

## 📊 Dataset Description  
The dataset contains **5000** customer records with attributes such as age, income, credit card usage, family size, and education level.  

### **Key Features**
| Feature         | Description |
|---------------|------------|
| Age            | Customer’s age (years) |
| Experience     | #Years of professional experience |
| Income        | Annual income (in $1000s) |
| Family        | Family size of the customer |
| CCAvg        | Avg. monthly spending on credit cards (in $1000s) |
| Education     | Education Level (1: Undergrad, 2: Graduate, 3: Advanced) |
| Mortgage      | House mortgage value (in $1000s) |
| Personal_Loan | Target Variable (0: No, 1: Yes) |
| Online        | Uses internet banking (0: No, 1: Yes) |
| CreditCard    | Uses other bank credit cards (0: No, 1: Yes) |

---

## 🔍 Exploratory Data Analysis (EDA)
- **Univariate & Bivariate Analysis** conducted using histograms, boxplots, and scatter plots.  
- **Key Insights**:
  - Higher-income customers are **more likely** to take loans.
  - Customers with **higher education levels (Graduate/Advanced)** are more receptive.
  - Holding a **Certificate of Deposit (CD) account** increases loan acceptance.
  - **Family size > 2.5** correlates with higher conversion rates.

---

## 🏗️ Data Preprocessing  
- **Missing Values**: No missing data found.  
- **Outlier Treatment**: Outliers were analyzed using boxplots.  
- **Feature Engineering**: No redundant features; ZIP Code was removed as it holds no predictive value.  

---

## 💻 Technologies Used  
- **Python (pandas, NumPy, scikit-learn, matplotlib, seaborn)**  
- **Machine Learning: Decision Trees with Pruning**  
- **Data Visualization: Matplotlib, Seaborn**  

---

## 🔥 Model Building - Decision Tree  
- A **Decision Tree Classifier** was implemented.  
- **Pre-pruning & Post-pruning** were applied to **reduce overfitting** and improve generalization.  
- Model **evaluation metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix  

---

## 📈 Model Performance & Evaluation  
| Model Version        | Train Accuracy | Test Accuracy | Overfitting Reduction |
|----------------------|---------------|--------------|-----------------------|
| Initial Decision Tree | **100%**       | **90%**      | High Overfitting ⚠️ |
| Pruned Model (Post)  | **95%**        | **92%**      | Reduced Overfitting ✅ |

- **Feature Importance Analysis** showed that **Income, CCAvg, Education, and CD Account** are the top predictors.
- **Confusion Matrix Analysis** helped reduce **false positives**, improving marketing efficiency.

---

## 💡 Actionable Insights & Business Recommendations  
🔹 **Target High-Income, High-Education Segments**: Customers with **income > 116.50K** and **higher education levels** should be a key focus.  
🔹 **Prioritize CD Account Holders**: CD account holders have a high likelihood of conversion.  
🔹 **Segment Campaigns Based on Credit Card Usage (CCAvg)**: Customers spending **> 2.95K per month** are more likely to take loans.  
🔹 **Focus on Families > 2.5 Members**: They show higher loan acceptance rates.  

---

## 📢 Evaluator Feedback & Scores  
### Exploratory Data Analysis (EDA)
**Evaluator's Comments:**
- The problem is clearly defined, focusing on predicting liability customers' likelihood of purchasing personal loans.
- Initial data overview is thorough, including data types, missing values, and basic statistics.
- Comprehensive visualizations (histograms, boxplots, scatter plots) effectively highlight relationships between variables.

**Score:** 10/10

### Data Pre-processing
**Evaluator's Comments:**
- No missing values, ensuring a complete dataset for modeling.
- Outliers and redundant columns were handled appropriately, maintaining dataset quality.

**Score:** 6/6

### Model Building - Decision Tree
**Evaluator's Comments:**
- Initial decision tree model was built and evaluated, showing perfect performance on the training set (indicating potential overfitting).
- Decision tree visualization effectively illustrates model complexity and the necessity for pruning.
- Both pre-pruning and post-pruning techniques were applied to enhance performance.

**Score:** 10/10

### Model Performance Evaluation and Improvement
**Evaluator's Comments:**
- Used appropriate metrics (accuracy, recall, precision, F1-score) to evaluate performance.
- Confusion matrices provide clear insight into training and test set performance, highlighting false positives.
- Applied both pre-pruning and post-pruning to reduce complexity and improve generalization.

**Score:** 20/20

### Actionable Insights & Recommendations
**Evaluator's Comments:**
- **Income & Loan Acceptance:** High-income individuals are more likely to accept loans, suggesting targeted marketing.
- **Credit Card Usage:** High spenders on credit cards show a higher loan acceptance rate, indicating potential conversion strategies.
- **Family Size & Income:** Families with children and high incomes have a greater likelihood of accepting loans, guiding segment-based marketing.

**Score:** 6/6

### Presentation & Notebook Quality
**Evaluator's Comments:**
- The presentation is well-structured with clear headings and explanations, making it easy to follow.
- Detailed analysis and explanations provide a deep understanding of the data and modeling.
- Effective use of visualizations enhances clarity and engagement.

**Score:** 8/8

### Final Score: **60/60** (Rounded Off)

### Conclusion
This project successfully predicts personal loan acceptance using a decision tree model. Insights derived from the analysis can help AllLife Bank optimize marketing campaigns, focusing on high-income individuals, credit card users, and families with children. The structured EDA, feature engineering, and model tuning steps ensure the reliability and interpretability of the results.

---

## 🏆 Key Takeaways  
- **Achieved a high-performing model (92% test accuracy)** with a well-balanced Decision Tree.  
- **Data-driven marketing insights** can significantly enhance AllLife Bank’s loan conversion rates.  
- **Strong business recommendations** tailored for targeted marketing campaigns.  



