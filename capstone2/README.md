# Capstone 2

Data science project containing all steps of the data science pipeline. The project is broken into
pieces via jupyter notebooks. Main goal is to investigate COVID-19 data and compare three models
for case number prediction including regression, fully connected neural network and convolutional neural networks.

[Data Cleaning and wrangling](notebooks/COVID19_data_cleaning.ipynb)
Covers the cleaning and wrangling of multiple COVID-19 datasets (see below) as well
as feature engineering. 

To get the JHU CSSE data: git clone https://www.github.com/CSSEGISandData/COVID-19

To get the OWID data: git clone https://www.github.com/owid/covid-19-data/

To get and store OxCGRT government response data: git clone https://github.com/OxCGRT/covid-policy-tracker/

To get and store Test Tracker data, go to https://finddx.shinyapps.io/FIND_Cov_19_Tracker/
    
    Choose "Tests and cases" dataset, select "All" as the entry number, 
    save as test_tracker_cases_and_tests.csv in same directory as notebooks.
    

[Exploratory Data Analysis](notebooks/COVID19_eda.ipynb)
Explore COVID-19 data and preliminary investigations of quarantine measures.

[Model prototyping](notebooks/COVID19_model_prototypes.ipynb)
Preview of different models, identifying proper data format for Keras API and scikit-learn 
API. 

[Regression analysis](notebooks/COVID19_regression.ipynb)
Investigation into the efficacy of a ridge regression model for case number prediction

[Fully connected neural network analysis](notebooks/COVID19_NN.ipynb)
Investigation into the efficacy of a two fully connected layers + activation layer 
neural network for the prediction of case numbers.

[Convolutional neural network analysis](notebooks/COVID19_CNN.ipynb)
Convolutional neural network with two convolutional layers, two fully connected layers and ReLU activation
for the prediction of future case numbers


To-do
-----
PEP 8 most of the notebooks.
Exploration of more architectures, especially the SeparableConv2D architecture which hasn't
been kept up to date with the other notebooks. 



