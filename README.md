# ML_Assignment
Documentation of ML assignment
Explanation

Download.ipynb
explanation

Loading the Dataset: The load_iris() function from sklearn.datasets returns a dictionary-like object with the data and feature names. We use this to create a pandas DataFrame, making it easier to analyze.
First Five Rows: The .head() method shows the first five rows of the DataFrame.
Dataset Shape: The .shape attribute provides the dimensions of the dataset (number of rows and columns).
Summary Statistics: The .describe() method calculates various summary statistics (mean, standard deviation, min, max, and quartiles) for each feature. 

Download1.ipynb
explanation

train_test_split Function: This function randomly splits the dataset into training and testing sets. test_size=0.2 specifies that 20% of the data should be allocated to the test set, and the remaining 80% will be used for training. random_state=42 ensures that the split is reproducible (you’ll get the same split each time you run the code).
Printing the Number of Samples: The .shape[0] attribute of the resulting arrays gives the number of samples (rows) in each set.

Download2.ipynb
explanation

Import Libraries: Import the necessary libraries for data manipulation, model fitting, and evaluation. Create/Load Dataset: Create a sample dataset or load your own. Split Dataset: Divide the data into training and testing sets. Fit Model: Train the linear regression model on the training data. Make Predictions: Predict salaries for the test set using the trained model. Evaluate Performance: Calculate and print the Mean Squared Error to evaluate model performance.
