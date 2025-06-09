📊 Statistical Analysis of Factors Influencing Student Success Using SPSS
This project applies IBM SPSS Statistics alongside Python to explore and analyze a dataset of student information. The aim is to uncover statistically significant factors that influence academic success, defined as whether a student passed or failed.

📁 Dataset
File: student_info.csv

Description: Contains demographic and academic records of students, including variables such as:

Gender

Age

Parental education

Study time

Final result (Pass/Fail)

🎯 Objectives
Prepare and clean the dataset for analysis.

Conduct hypothesis tests (Chi-Square, T-tests, ANOVA) to assess variable significance.

Build and interpret a binary logistic regression model to predict student success.

Identify and report key predictors of performance.

🔬 Statistical Methods
Test	Purpose
Chi-Square Test	Test association between categorical variables (e.g., gender vs result)
T-Test (Independent)	Compare means between two groups (e.g., study hours by result)
One-Way ANOVA	Analyze variance among 3+ groups (e.g., parental education level)
Binary Logistic Regression	Predict probability of student passing/failing based on predictors

🧰 Tools & Technologies
IBM SPSS Statistics – Hypothesis testing & regression modeling

Python – Preprocessing and visualization using pandas, seaborn, matplotlib

Jupyter Notebook – Exploratory and statistical analysis workflow

Git / GitHub – Version control and project sharing

📌 Key Findings
Gender has a statistically significant association with academic outcomes.

Study time is significantly higher among students who passed.

Parental education and study hours are strong predictors of student success.

The logistic regression model achieved 81% accuracy in predicting outcomes.

📊 Visuals
All visuals used in the analysis are stored in the /visuals folder:

chi_square_gender_vs_result.png

ttest_study_hours.png

