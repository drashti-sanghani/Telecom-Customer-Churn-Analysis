# **Telecom Customer Churn Prediction**

## **Overview**
This project aims to predict customer churn for a telecom company using machine learning techniques. The goal is to build a predictive model that helps identify customers who are likely to churn, enabling the company to take proactive retention measures. The dataset contains customer information, including demographics, subscription details, and usage patterns. Machine learning algorithms are applied to analyze these factors and predict churn.

## **Project Workflow**
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA)**: Performing visual analysis to understand patterns and relationships in the data.
3. **Model Training**: Several machine learning models such as Naives Bayes, Logistic Regression, Random Forest, and XGBoost are trained.
4. **Model Evaluation**: Evaluation of models based on accuracy, precision, recall, F1-score, and the ROC curve to determine the best performing model.
5. **Results Interpretation**: Interpreting the results to provide actionable insights for improving customer retention.

## **Key Features Analyzed**
- **Customer Demographics**: Age, gender, and senior citizen status.
- **Subscription Details**: Contract type (monthly, one-year, two-year), payment method, and paperless billing.
- **Usage Data**: Monthly charges, total charges, and tenure.
- **Service Usage**: Features like internet service, tech support, streaming services, and device protection.

## **Results**
- The best performing model was **Random Forest**, which achieved the highest accuracy and recall rate. 
- **Logistic Regression** performed well in terms of interpretability but had slightly lower performance compared to Random Forest and XGBoost.
- The **ROC curve** analysis showed that all models performed well, but Random Forest had the best balance between precision and recall.

## **Tools and Technologies**
- **Programming Language**: Python
- **Data Analysis & Preprocessing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning Libraries**: Scikit-learn, XGBoost
- **Notebook Environment**: Jupyter Notebook

## **Conclusion**
The customer churn prediction model can help telecom companies proactively identify at-risk customers, enabling them to implement retention strategies. The Random Forest model, with its high recall and precision, provides an effective tool for predicting customer churn. This project can be extended by including additional customer features or exploring advanced techniques such as ensemble learning.

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom-customer-churn.git
   
2. Navigate into the project directory:
   ```bash
   cd telecom-customer-churn-analysis

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook

5. Run the notebook to explore the data, preprocess it, and train the models.

## **Dataset**
The dataset used in this project is a publicly available telecom customer churn dataset. It contains various features like customer demographics, subscription details, and usage information. The dataset has columns such as SeniorCitizen, tenure, MonthlyCharges, Churn, Contract, PaymentMethod, and more.

## **Acknowledgement**
I would like to thank **NYC Open Data** for providing the dataset used in this project, which was essential for analyzing customer churn patterns.

I am also grateful for the overall support and resources that helped me throughout the development of this project.

## **Future Work**
- Deployment of the churn prediction model as a web application for real-time use cases.
- Incorporation of additional customer metrics and external data sources to enhance predictive accuracy.
- Development of a feature importance dashboard for better interpretability of model outcomes.
