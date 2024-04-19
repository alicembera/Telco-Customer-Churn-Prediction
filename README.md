# Costumer-Churn-Prediction-and-Retention-Strategies-for-Teleco-Company
This project aim was to identify the key indicators of customer churn for a telecommunications company and develop a model to predict which customers are likely to churn. The primary objective of this project is to develop a classification model for churn analysis to aid in customer retention efforts. Churn analysis focuses on predicting whether customers are likely to leave or continue their relationship with the company. By identifying customers at risk of churning, the company can take proactive measures to retain them, thus increasing revenue and profit margins.

I used Python and Jupyter notebook for this project.
## Column names and description:
The data for this project is in differnt files and will be loaded into the notebook. The following describes the columns present in the data.

Gender -- Whether the customer is a male or a female

SeniorCitizen -- Whether a customer is a senior citizen or not

Partner -- Whether the customer has a partner or not (Yes, No)

Dependents -- Whether the customer has dependents or not (Yes, No)

Tenure -- Number of months the customer has stayed with the company

Phone Service -- Whether the customer has a phone service or not (Yes, No)

MultipleLines -- Whether the customer has multiple lines or not

InternetService -- Customer's internet service provider (DSL, Fiber Optic, No)

OnlineSecurity -- Whether the customer has online security or not (Yes, No, No Internet)

OnlineBackup -- Whether the customer has online backup or not (Yes, No, No Internet)

DeviceProtection -- Whether the customer has device protection or not (Yes, No, No internet service)

TechSupport -- Whether the customer has tech support or not (Yes, No, No internet)

StreamingTV -- Whether the customer has streaming TV or not (Yes, No, No internet service)

StreamingMovies -- Whether the customer has streaming movies or not (Yes, No, No Internet service)

Contract -- The contract term of the customer (Month-to-Month, One year, Two year)

PaperlessBilling -- Whether the customer has paperless billing or not (Yes, No)

Payment Method -- The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic))

MonthlyCharges -- The amount charged to the customer monthly

TotalCharges -- The total amount charged to the customer

Churn -- Whether the customer churned or not (Yes or No)

## Hypothesis
Hypothesis 1 Null Hypothesis (Ho): There is no significant difference in churn rates between customers with shorter and longer tenure.

Alternative Hypothesis (Ha): There is a significant difference in churn rates between customers with shorter and longer tenure.

Hypothesis 2 Null Hypothesis (Ho): There is no significant difference in churn rates between customers with higher and lower monthly charge.

Alternative Hypothesis (Ha): There is a significant difference in churn rates between customers with higher and lower monthly charge.

## Questions
- What is the average tenure of customers who churned compared to those who stayed?
- Do customers with partners or dependents have a lower churn rate?
- How does the presence of multiple lines affect customer churn?
- Is there a correlation between the contract term (Contract) and customer churn?
- What are the common payment methods (Payment Method) among customers who churned?
-  How does the availability of tech-related services (e.g., OnlineSecurity, TechSupport) impact churn rates?
- What percentage of customers who churned had streaming services (StreamingTV, StreamingMovies)?
- Is there a difference in churn rates between senior citizens and non-senior citizens?
- How does the total amount charged to customers (TotalCharges) correlate with churn behavior?
- How does the contract affect churn rates?

  ## Dataframe and Datatypes Understanding 
The dataset was loaded into a Pandas DataFrame using the pd.read_csv function. The dataset contained **20 columns/features and 5043 rows**.

**Datatypes** 

This output of the dataframe.info() revealed that the 20 columns in  with their corresponding data types had no missing values (since all columns have 5043 non-null values), but the TotalCharges column was in object instead of float64. This suggests that there may be some non-numeric values in this column that need to be cleaned.

## Summary of findings from the analysis 
Below are some findings drawn from the jupyter notebook for your kind attention 
1. Data handling packages like pandas and numpy were used
2. Packages for feacture processing, machine learning and hyperparemeter tuning were also used to acheive the object of the analysis
3. Other packages such as tabulate, os and  warnings  were also used.
4. Regarding the hypothesis, 
- There is a significant difference in churn rates between customers with shorter and longer tenure. 
- There is a significant difference in churn rates between customers with higher and lower monthly charges.
5. The best performing model was **Logistic Regression**

## Conclusion

Churn analysis represents a strategic initiative aimed at leveraging data-driven insights to mitigate customer attrition and foster long-term loyalty. By harnessing the power of classification models, the company endeavors to enhance customer retention efforts, drive sustainable revenue growth, and maintain a competitive edge in the dynamic marketplace.

### Thank you!

Link to article on Medium:


### Power BI Visualizations




## Author 
Alice Mbera



  


