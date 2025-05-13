# Using Predictive Modeling on Medical Data
This project is two-fold, with one section examining data relating to heart disease and one section examining data relating to Alzheimer's. Both sections employ multiple models with the purpose of predicting diagnoses of each disease with high accuracies. Both datasets were found on kaggle.com and required minimal data cleaning, so the emphasis of the project was placed on the implementation and tuning of the machine learning models. 

## Heart Disease
#### Cleaning and EDA
- Minor cleaning included encoding all categorical variables and checking for null values 
- Used Seaborn and matplotlib to plot simple charts exploring the makeup of this data
#### Naive Bayes
- Utilized the scikit-learn library to create a naive bayes model 
- Yielded an accuracy of 72.5%
#### K Nearest Neighbors
- Hyperparameterized using a grid search cross validation
- Yielded an accuracy of 66%
## Alzheimer's Disease
#### Cleaning and EDA
- Encoded all categorical variables and eliminated all instances of null values
- Used Seaborn and matplotlib to plot simple charts exploring the makeup of this data
#### Principal Componet Analysis
- Created a correlation map, performed PCA, and plotted subsequent biplots to show the relationship between independent variables
- Ultimately, this analysis showed the lack of a need for dimensionality reduction for this data
#### Random Forest Classification
- Utilized SMOTE package to artificially resample data because the minority class was underrepresented in the data and predictive models were not yielding true accuracies
- Hyperparameterized the model using a grid search cross validation
- Yielded an accuracy of 73.7%
#### Artificial Neural Net
- Scaled data using a standard scaler in order to be able to create a neural net
- Used tensorflow package through Keras to create an artificial neural net
- Yielded an accruacy of 68.7%
