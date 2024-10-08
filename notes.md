# Machine Learning
## Data Preprocessing includes:
    -   Importing the lib
    -   Importing the dataset
    -   take care of missing data
    -   Encode categorical data
        -   Encode independent variables
        -   Encode dependent variables
    -   Split train and test data
    -   feature scaling
### How to deal with missing data?
- Delete the row and ignore
- Replace the missing values with average of all the salaries.
### What to do with categorical data?
- Encode it
  - Dependant variable
  - Independent variable
- One Hot Encoding : for example for countries. when there is no ordering.
- Label Encoding: No|Yes for Y can be encoded to 0,1
### Feature scaling
- To have all teh values of features in same range
- Should not be done at features which were encoded
- Only for numerical values
- Two types
  - Standardization (-2 to +2)
  - Normalization (0 to 1)
## Regression
 - To predict the real value like salary
 - [GeeksForGeeks Article](https://www.geeksforgeeks.org/types-of-regression-techniques/)
### Simple Linear Regression
### Multiple Linear Regression
- No need to apply feature scaling in multiple linear regression
## Building a Model
- All IN
- Backward Illimination (fastest)
- Forward Selection
- Bidirectional Elimination
- Score Comparison
### Polynomial Regression
### Support Vector for Regression (SVR)
### Decision Tree Regression
### Random Forest Regression

## SVR - Support Vector Regression
- A tube instead of a linear line

## Logistic Regression
- Used to calculate Category like yes or no
- To get best curve calculate curve with best likelihood value.

## K-Nearest Neighbor
- Calculate the distance of neighbor's upto k for ex 5 and put the new point in that category where max points are there.

## SVM
- Lines between extreme one type of point or classification like apples (Negative hyperplane) and first another type of point like oranges (positive hyperplane) points.
- Used to classify apples or oranges.

## Decision tree classification
- Yes/No ladder
- Old method
- reborn with upgrades
  - random forest
  - gradient boosting

## Random forest classification
- ensemble learning : multiple algo to create one algo
- 


# General Steps
- Import Libraries
- Split dataset into training and testing set
- Feature scaling
- Training
- Predicting single result
- Predicting test results


# Questions?
- When to use SVR?
- What is feature scaling? When to use it?
  - Linear reg should not use feature scaling
  - Implicit equation and implicit relation between dep variable y. we should apply feature scaling
  - When to use decision tree regression vs Linear regression?
- What is confusion matrix?
- What is Naive Based?
