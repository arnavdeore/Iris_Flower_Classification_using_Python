# Iris_Flower_Classification_using_Python
Classify iris flowers into different species based on petal and sepal dimensions.

# **Iris Flower Classification Project**

## **Project Description**
- This project aims to classify iris flowers into three species (**setosa**, **versicolor**, **virginica**) based on their sepal and petal dimensions. This project demonstrates the fundamental concepts of supervised learning, including data visualization, model training, evaluation, and deployment. We will use 
  Scikit-learn's built-in Iris dataset.
 
    - Step 1:	**Load the Iris Dataset**
        1.	The Iris dataset is a classic dataset available in the Scikit-learn library. It contains the measurements of sepals and petals for three species of iris flowers: setosa, versicolor, and virginica.
           Explanation:
              1.	load_iris: Loads the dataset.
              2.	DataFrame: This makes data handling and visualization easier by converting the dataset into a tabular format.
              3.	Species mapping: Adds a column with species names for better readability.
        2.	Enhanced Data Exploration
           Explanation:
              1)	Statistical Summary: Understand each feature's range, mean, and standard deviation.
              2)	Missing Values: Ensures data quality by checking for null or missing entries.
              3)	Feature Distribution: Visualizes the spread of each feature to detect skewness or outliers.
    - Step 2:	Visualize Relationships Between Features**
        1.	Visualizations help understand the relationships between features and how they correlate with the target class.
            Explanation:
          	       1)	Pairplot: Shows scatter plots between features and helps visualize clustering between species.
          	2)	Heatmap: Displays the correlation between features, indicating which ones might be more significant for classification.
    - Step 3:	Train a Classification Model
         1. We will train a Logistic Regression model as an example. For experimentation, you can replace it with K-Nearest Neighbors (KNN).
            Explanation:
                     1)	train_test_split: Splits the dataset into training and testing sets (80% training, 20% testing).
                     2)	Logistic Regression: A simple linear model suitable for classification problems.
                     3)	Accuracy: Evaluates how well the model performs on unseen data.
