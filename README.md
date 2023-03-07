# Analyzing-WADA-s-Anti-Doping-Sanctions.
EDA and Modeling
Obtained data from World Anti-Doping Agency (WADA) which included 829 rows and 4 columns (sport, substance_reason, sanction_terms, sanction_announced).

Conducted various data cleaning steps such as checking for missing values, null values, and duplicates.
Performed feature engineering by adding new columns from existing ones and removing irrelevant columns.
Checked for outliers and cleaned the data.
Encoded the data to numeric for modeling.
Visualized the data using different charts and plots to detect patterns.
Conducted statistical analysis and used the chi-squared test to determine the correlation between variables.
Built a model using logistic regression, xgboost, and bagging, and validated it using cross-validation.

Obtained valuable insights from the analysis, including:
Cycling had over 100 sanctions.
The most frequently detected substances were Androgenic Anabolic, Cannabinoids, and Ostarine.
The top 5 sports with the most doping cases were Cycling, MMA, Weightlifting, Track and Field, and Wrestling.
The months of December and August had the most sanctions.
There was a significant association between sanction terms and substance reasons, indicating that they are not independent.
The years 2003 and 2005 had the least sanctions.
The most commonly used sanction term was 2-4 years out of sport.
62% of sanctioned athletes lost their results.
The period between 2017-2019 had the most sanctions.
Longer sanction terms were associated with more severe consequences, such as loss of results.
As time passed, there were more advanced methods for detecting doping, leading to fewer cases of loss of results.
The model had an accuracy score of 0.94 for predicting.
