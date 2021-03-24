# Capstone 1

Data science project containing all steps of the data science pipeline. The project is broken into
pieces via jupyter notebooks.

[Data Cleaning and wrangling](notebooks/Lending_club_data_cleaning.ipynb)
Covers the cleaning and wrangling of the Lending club loan dataset.

[Exploratory Data Analysis](notebooks/Lending_club_data_story.ipynb)
Explores the features of the lending club loan dataset to get a better feel for the data and 
determine any complications which may occur in modeling.

[Statistical Analysis](notebooks/Lending_club_statistical_analysis.ipynb)
Investigation and exploration of the different distributions of independent variables
which occur in the dataset.

[Loan Outcome Classification](notebooks/Lending_club_loan_classification.ipynb)
Modeling notebook for "step one" of the two-step recommendation system. Comparison between 
Logistic regression and Random Forest for predicting loan outcome. 

[Loan Recovery Regression](notebooks/Lending_club_recovery_regression.ipynb)
Modeling notebook for "step two" of the two-step recommendation system. Comparison
of ridge regression and SGD for prediction of loan recoveries.  

# Data

To run the notebooks, unzip loan.csv into data folder. Then run 
```Lending_club_data_cleaning.ipynb``` to generate the other .csv files used for EDA and modeling. 



