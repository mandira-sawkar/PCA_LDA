> **Objective:**
Visualizing high dimensional data using PCA and doing dimensionality
reduction to check the explained variance using the PCA model. Training a
Linear Discriminant Analysis(LDA) model to check if the product has been
shipped or canceled.
> **Problem Statement:**
XYZ.com is an e-commerce company based in Argentina. Due to the covid
crisis and lockdown XYZ.com is facing lots of issues from the dealer and the
shipment team. XYZ.com has lots of product data where various shipping and
sales details of each product have been mentioned. XYZ.com wants to find out
which of the products has been shipped and which of the products has been
canceled to reduce customer escalation. As a data-scientist, we have to train a
PCA model to visualize its higher-dimensional data and we have to train an
LDA(Linear Discriminant Analysis) model to predict which of the products has
been shipped and which of the products has been canceled.

● Data Loading and Exploration.
1. Clean and prepare the data.
2. Plot relevant graphs to understand the data.

● PCA FOR VISUALIZATION
1. Take the help of PCA to reduce the data to 2 dimensions.
2. Take the first and second principal components and plot a scatter plot
with the labels.
3. Write the intuitions about the scatter plot.

● PCA FOR DIMENSION REDUCTION
1. Fit the PCA model on the data and plot a graph between n_components
and cumulative explained variance.
2. In how many components we are getting approximately 90% of explained
Variance.

● LDA
1. Split the dataset into train and test parts.
2. Train a Linear Discriminant Analysis(LDA) model on the train data. Do
fit_transform on the train data and only transform on the test data.
3. Train a RandomForest classifier model on the transformed train and test
data. Print the accuracy score.
