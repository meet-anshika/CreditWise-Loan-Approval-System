# CreditWise-Loan-Approval-System

🔍 Project Overview
CreditWise Loan Approval System is a Machine Learning–based loan approval prediction system developed using Python and Jupyter Lab.
The project analyzes applicant financial and personal details to predict whether a loan will be approved or rejected, following a complete end-to-end Data Science pipeline.
This project focuses on EDA, preprocessing, feature engineering, multiple ML models, and performance comparison

🎯 Objective
To build a reliable loan approval prediction system that:
- Reduces manual decision-making
- Uses data-driven insights
- Compares multiple ML algorithms to select the best-performing model

🛠️ Tech Stack
- Python
- Jupyter Lab
- Pandas & NumPy – Data manipulation
- Matplotlib & Seaborn – Data visualization
- Scikit-learn – Machine Learning & preprocessing

🔄 Project Workflow
1️) Data Loading & Understanding
- Loaded dataset using Pandas
- Checked shape, datatypes, and missing values
- Used .info() and .describe() for statistical overview

2️) Handling Missing Values
- Numerical features → Median Imputation
- Categorical features → Most Frequent Imputation
- Ensured dataset consistency before modeling

3️) Exploratory Data Analysis (EDA)
Performed detailed EDA using:
- Pie chart for loan approval distribution
- Bar plots for categorical variables
- Histograms for income distributions
- Boxplots for income vs loan approval
- Correlation heatmap to analyze feature relationships

4️) Encoding Categorical Variables
- Label Encoding for ordinal features
- One-Hot Encoding for nominal features
- Ensured all features are machine-readable

5️) Feature Engineering
- Created Debt-to-Income Ratio (DTI_Ratio)
- Applied log transformation on skewed income features
- Selected important features based on correlation analysis

6️) Train-Test Split & Scaling
- Split data into training and testing sets
- Applied StandardScaler for feature normalization

🤖 Machine Learning Models Used
🔹 Logistic Regression
🔹 K-Nearest Neighbors (KNN)
🔹 Naive Bayes (GaussianNB)

📈 Model Evaluation Metrics
- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

🏆 Final Conclusion

- Naive Bayes performed best for the CreditWise Loan Approval System
- Logistic Regression was the second-best model

Overall, Naive Bayes is the most suitable model for this dataset.

🚀 How to Run the Project
1) Clone the repository:
   git clone https://github.com/meet-anshika/CreditWise-Loan-Approval-System.git
2) Open Jupyter Lab:
    jupyter lab
3) Run the notebook:
   Credit_wise.ipynb

👩‍💻 Author
Anshika Kela
B.Tech – CSE (Data Science)
