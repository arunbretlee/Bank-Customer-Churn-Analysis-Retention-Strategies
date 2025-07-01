# **Bank Customer Churn Analysis & Retention Strategies**

## **📝 Project Description**

This project aims to comprehensively analyze customer churn within a retail banking context, leveraging a dataset of bank customer demographics, financial behavior, and transaction history. The primary objectives are to:

1. Identify the key factors and customer segments that are most susceptible to churn.  
2. Develop data-driven insights and actionable recommendations to improve customer retention and loyalty.  
3. Showcase the power of data analysis and visualization tools in solving real-world business problems.

The analysis is conducted using Python for robust data manipulation, exploration, and potentially predictive modeling, with the findings powerfully communicated through an interactive dashboard built in Tableau.

## **📊 Data Source**

The analysis is based on the Bank Customer Churn Prediction.csv dataset, comprising 10,000 entries and 12 distinct features. This dataset provides a rich view into customer characteristics and their relationship with churn.

**Dataset Columns:**

* customer\_id: Unique identifier for each bank customer.  
* credit\_score: A numerical value representing the customer's creditworthiness.  
* country: The customer's country of residence (e.g., France, Germany, Spain).  
* gender: The customer's gender.  
* age: The customer's age in years.  
* tenure: The number of years the customer has been with the bank.  
* balance: The customer's average account balance.  
* products\_number: The number of bank products (e.g., savings account, credit card, loan) the customer holds.  
* credit\_card: Binary indicator (1 if the customer has a credit card, 0 otherwise).  
* active\_member: Binary indicator (1 if the customer is an active member, 0 otherwise).  
* estimated\_salary: The customer's estimated annual salary.  
* churn: The target variable; binary indicator (1 if the customer churned, 0 otherwise).

## **🛠️ Tools & Technologies**

* **Python:**  
  * pandas: For efficient data loading, cleaning, manipulation, and preliminary aggregations.  
  * numpy: For numerical operations and array manipulation.  
  * matplotlib & seaborn: For static exploratory data analysis (EDA) visualizations.  
  * scikit-learn (Optional): If a predictive churn model was implemented (e.g., Logistic Regression, Decision Tree Classifier).  
* **Data Visualization & Business Intelligence:**  
  * **Tableau**: For creating a dynamic, interactive dashboard to present key findings and insights.

## **🚀 Project Steps & Methodology**

The project followed a structured data analysis workflow:

1. **Data Loading & Initial Assessment:** Loaded the dataset and performed initial checks for data types, completeness (no missing values were found), and basic statistics.  
2. **Exploratory Data Analysis (EDA) with Python:**  
   * Calculated the **overall churn rate** and **segmented churn rates** across various dimensions (country, gender, age groups, products number, active member status, credit score, tenure, balance ranges).  
   * Visualized data distributions and relationships using Python to uncover initial patterns and potential churn drivers.  
3. **Data Preprocessing & Feature Engineering:**  
   * Cleaned data where necessary (e.g., ensuring correct data types for numerical columns).  
   * Created Age Bins and Balance Bins to analyze churn across specific ranges.  
4. **Predictive Modeling (Optional \- if you did this):**  
   * Built a classification model (e.g., Logistic Regression) to predict customer churn based on key features.  
   * Evaluated model performance and identified feature importance to understand top churn predictors.  
5. **Interactive Dashboard Development with Tableau:**  
   * Exported the cleaned and processed data from Python into a CSV format (e.g., customerChurn.csv).  
   * Connected Tableau to the prepared data.  
   * Designed and constructed an interactive dashboard comprising KPIs, comparative bar charts, and distribution plots to visually convey complex relationships and insights.

## **🎯 Key Findings & Insights**

The analysis yielded several critical insights into customer churn:

* **Overall Churn Rate:** The bank is experiencing an overall churn rate of approximately **20.37%**.  
* **Product Holding Paradox:** Customers holding **3 or more bank products exhibit an alarmingly high churn rate (over 80%)**, in stark contrast to the remarkably low churn (around 7.6%) observed among customers with **exactly 2 products**. This is a major red flag indicating potential dissatisfaction or complexity with a high number of products.  
* **Geographic Vulnerability:** Customers in **Germany** show a significantly higher churn rate (32.44%) compared to France (16.15%) and Spain (16.67%).  
* **Gender Disparity:** **Female customers** are more prone to churn (25.07%) than male customers (16.46%).  
* **Engagement is Key:** **Inactive members** churn at a significantly higher rate (26.85%) than active members (14.27%).  
* **Tenure & Age Impact:** Newer customers (first 1-2 years) and certain age groups show elevated churn risks.  
* **Balance & Credit Score Influence:** Customers with zero balances often churn, and churn tends to be higher among those with lower credit scores.

## **💡 Actionable Recommendations**

Based on these findings, the following strategies are recommended to mitigate customer churn:

1. **Strategic Product Portfolio Review:** Investigate the underlying reasons for high churn among customers with 3+ products. This requires understanding pain points, perceived value, and service experience for these segments.  
2. **Targeted Retention Campaigns:** Develop specific, localized retention strategies for customers in Germany and tailored approaches for female customer segments.  
3. **Boost Customer Engagement:** Implement proactive programs to convert inactive members into active users through personalized communication, value-added services, or loyalty incentives.  
4. **Onboarding & Lifecycle Nurturing:** Enhance the onboarding experience for new customers and create specific engagement programs for customers at critical tenure milestones.  
5. **Proactive Risk Identification:** Leverage these insights to build predictive models that can identify high-risk customers early, allowing for timely, personalized interventions.  
6. **Review Balance-Specific Policies:** Address the high churn for zero-balance accounts, potentially through re-engagement offers or streamlining account closure processes.

## **🏃 How to Run the Project**

1. **Clone the Repository:**  
   git clone \[Your GitHub Repository URL\]  
   cd \[Your Project Folder Name\]

2. **Set up Python Environment:**  
   * It's recommended to use a virtual environment:  
     python \-m venv venv  
     source venv/bin/activate  \# On Windows: \`venv\\Scripts\\activate\`

   * Install the required Python libraries:  
     pip install pandas numpy matplotlib seaborn scikit-learn \# Adjust if you didn't use scikit-learn

3. **Data:**  
   * Ensure the Bank Customer Churn Prediction.csv file is placed in the root directory of the project (or wherever your Python script expects it).  
4. **Run Python Analysis:**  
   * Open and execute the Jupyter Notebook (Customer\_Churn\_Analysis.ipynb) to perform data cleaning, EDA, and any modeling. This will generate your processed CSV file (e.g., customerChurn.csv).  
5. **View Dashboard:**  
   * Open the \[Your\_Tableau\_Workbook.twbx\] file in Tableau Desktop/Reader to explore the interactive dashboard.

## **🤝 Contribution**

Arun Dara

https://www.linkedin.com/in/arundara/