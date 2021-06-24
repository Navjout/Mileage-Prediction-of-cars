# Mileage-Prediction-of-cars
In this project we aim to predict mileage per gallon(mps) using various technical specifications (features) as input to the regression algorithms. 

## Database Description:

The data is technical spec of cars. This dataset is a slightly modified version of the dataset provided in the StatLib library. In line with the use by Ross Quinlan (1993) in predicting the attribute "mpg", 8 of the original instances were removed because they had unknown values for the "mpg" attribute. The original dataset is available in the file "auto-mpg.data-original".

"The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes." (Quinlan, 1993)

Number of Instances: 398

Number of Attributes: 9 including the class attribute

## Attribute Information:

mpg: continuous cylinders: multi-valued discrete displacement: continuous horsepower: continuous weight: continuous acceleration: continuous model year: multi-valued discrete origin: multi-valued discrete car name: string (unique for each instance) Missing Attribute Values: horsepower has 6 missing values

# Steps:

### Task 1 : Importing the LIbraries

Imported the libraries:
1. pandas
2. Numpy
3. Seaborn
4. Matplotlib

## Task 2 : loading the dataset
Here we loaded the dataset and saw top 10 and last 10 car information records and dropped the car name.

### Task 3 : Data Preprocessing
Here we checked for null values and saw horsepower data

### Task 4 : Correlation matrix
Plotting the heatmap of the correlation

### Task 5 : Univariate Analysis
Plotted Graph of cylinder count

Graph of model year count

Graph of origin count

### Task 6 : Multi-variate Analysis

Boxplot of cylinder vs mpg

Boxplot of model year vs mpg

### Task 7 : Train and test data split

### Task 8 : Build the model

### Task 9 : polynomial regression

# Conclusion
Accuracy score improves in the case of polynomial regression compared to the linear regression because it fits data much better. In this project, what we learned:
1. Loading the dataset
2. Univariate analysis
3. multivariate analysis
4. Linear regression
5. Polynomial Regression






