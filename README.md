### Housing and Bank Dataset Analysis

#### Question 1:

- **Housing Dataset:**
  - Contains information about 545 houses with the price column as a dependent variable.
  - Other columns act as independent variables affecting the prices.

- **Tasks:**
  a) Read the csv file "Housing.csv" into a Pandas DataFrame.
  b) Define price as the dependent variable (Y) and area, bedrooms, bathrooms, stories, and furnishing status as independent variables (X) using one-hot encoding.
  c) Split the dataset into training (70%) and test set (30%).
  d) Use the sklearn library to perform regression on the training dataset.
  e) Predict the price of a house with given features.
  f) Predict the prices of all houses in the test set and compare predicted values with actual values.

#### Question 2:

- **Bank Dataset:**
  - Contains data on 5000 customers with demographic information, relationship with the bank, and response to the last personal loan campaign.

- **Tasks:**
  a) Read the csv file "Bank.csv" and provide a summary of the DataFrame.
  b) Define 'Personal Loan' as the class (Y) variable and Age, Experience, Income, and Education as independent (X) variables.
  c) Split the dataset into training (80%) and test set (20%).
  d) Use Logistic Regression model on the training dataset and evaluate on the test set.
  e) Display the result as a confusion matrix and accuracy.
  f) Create predictions for five new data points for X variables (Age, Experience, Income, and Education).
