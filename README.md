Credit Risk Modelling Application

This project is an interactive web-based credit risk modeling application that calculates the probability of loan default, assigns a credit score, and provides a rating based on user inputs. Developed using a combination of machine learning and web technologies, this application offers insights into credit risk for financial institutions and users alike.
Features

1. Input Fields:

Users can provide the following inputs:

Age: Borrower's age (in years).

Income: Annual income of the borrower.

Loan Amount: Amount of the loan being applied for.

Loan Tenure: Duration of the loan (in months).

Avg DPD: Average Days Past Due for prior delinquencies.

Delinquency Ratio: Ratio of past delinquencies to total accounts.

Credit Utilization Ratio: Percentage of credit utilization.

Open Loan Accounts: Number of active loan accounts.

Residence Type: Select from "Owned," "Rented," or "Mortgage."

Loan Purpose: Choose the purpose of the loan, e.g., Education, Home, Auto, or Personal.

Loan Type: Specify the type of loan, i.e., "Secured" or "Unsecured."

2. Real-time Calculations:

Loan-to-Income Ratio: Dynamically calculated and displayed based on user inputs.

3. Predictions:

Default Probability: The likelihood that the borrower will default.

Credit Score: A score scaled between 300 and 900, where a higher score indicates better creditworthiness.

Rating: A qualitative assessment ("Poor," "Average," "Good," or "Excellent") based on the credit score.

4. User Interface:

Built with Streamlit, ensuring a clean, user-friendly experience.

Interactive elements like number inputs and dropdowns for ease of use.

Technologies Used

Programming and Libraries:

Python: Core programming language.

Pandas: For data manipulation.

NumPy: For numerical computations.

Matplotlib and Seaborn: Used during exploratory data analysis (EDA).

Scikit-learn: For implementing the Logistic Regression model and scaling features.

Joblib: To save and load the trained model and its components.

Streamlit: To build the web-based interface.

Machine Learning Techniques:

Logistic Regression model trained to predict credit default risk.

Feature scaling using MinMaxScaler to normalize inputs.

Calculations include probabilities and custom credit scoring.

Files in the Project

main.py: Contains the Streamlit code for the user interface.

prediction_helper.py: Includes functions for preparing input data, making predictions, and calculating credit scores.

artifacts/model_data.joblib: Pre-trained Logistic Regression model and associated metadata (e.g., scaler, feature list).

requirements.txt: Lists the necessary Python libraries for the application.
How It Works

Users provide details about age, income, loan amount, and other financial factors.

The input data is processed and scaled using pre-saved parameters.

The Logistic Regression model predicts the default probability.

Credit score and rating are derived from the probability.

Results are displayed on the web app in real-time.

Acknowledgments

Developed by Beekesh Singh, leveraging expertise in:

Data Science

Machine Learning

Web Application Development




