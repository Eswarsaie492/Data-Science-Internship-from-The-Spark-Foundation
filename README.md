# Internship from The Spark Foundation
Data Science Tasks

K-Means Clurstering:

- Explored Iris Dataset using K-Means Clustering Algorithm which is an Unsupervised Machine Learning Model.
- The Objective of K-Means Clustering is to group similar data points together and discover underlying patterns. In the process, K-Means requires a fixed number of Clusters i.e., (k) in a dataset. The centre of the cluster is called Centroid. So, we define ‘k’ as the number of centroids we need in the dataset. K-Means Algorithm identifies the ‘k’ number of centroids and allocates every data point to the nearest cluster.
- The K-Means Clustering Algorithm starts with randomly selected centroids and performs iterative calculations to optimize the positions of the Centroids. It halts either when the centroids are stabilized or when the defined number of iterations is achieved.
- In the given Iris dataset, initially, I’ve imported the required Libraries like pandas, numpy, matplotlib and sklearn. Later I’ve worked on knowing the details of the data and plotted the data using scatter plot for better understanding. 
- As mentioned, by choosing random value of k, in some cases, K-Means can result in bad clusters. Here, K-Means++ helps to initialize the cluster. So, we plot a graph called as Elbow Curve, in which, the number of clusters on x-axis and the Evaluation metric on y-axis. The cluster value where the Evaluation Metric becomes constant is the right cluster value. 
- From the Elbow curve, got the optimum value of ‘k’ as 3 and fit the model and Visualized by plotting the clusters and centroids of the respective clusters.


Linear Regression:

- Explored Student Dataset using Linear Regression Algorithm which is a Supervised Machine Learning Model. The dataset contains only two features i.e., No. of Hours studied and Marks Scored.
- The Linear Regression I’ve used here is Simple Linear Regression because of the single input variable (Hours) and predict the target variable (Marks) based on the given dataset. Making predictions using Linear Regression is simple and represented as:  y = B0 + B1 * x1, where y is the target variable, B0 is the bias coefficient and B1 is the coefficient of the input variable x1.
- I’ve prepared the data by finding few inner details and by splitting the data into train and test datasets. Now, I’ve trained and fit the model and plotted the regression line. After making predictions with the test data, compared the output values of actual test data and predicted data and evaluated the model to find the Mean Absolute error to be 4.18. 


Decision Tree Algorithm:

- Explored Iris Dataset using Decision Tree Algorithm which is a Supervised Machine Learning Model.
- In Decision Tree Algorithm, the best attributes are placed at the root of the tree, split the training set into subsets and repeat until we find the leaf nodes for all the branches in the tree. The process of identifying the attributes for the root node is called as attribute selection and for this we have two selection measures. One is Information Gain and the other one is Gini Index.
- Information Gain is measure of change in the entropy. Entropy is the measure of uncertainty of a random variable. The higher the entropy the more the information content.  Gini Index is the metric to measure how often a randomly chosen element would be incorrectly identified. So, an attribute with lower Gini Index is preferred. 
- I’ve prepared the dataset by finding the details and features and split the data into train and test datasets. Later I’ve trained and fit the model and got the accuracy score of 93%, which is great and visualized by plotting the tree for better understanding.


Exploratory Data Analysis:

- Explored Superstore Dataset using Exploratory Data Analysis to find some insights from the dataset.
- Exploratory data Analysis is the critical process of performing initial investigations on the data to discover patterns with the help of summary statistics and graphical representation.
- As the whole process is a try-check and see method, I’ve started with initial findings of the data such as Total no. of rows and columns, info and description of the data. - -- Later I’ve checked for the unique values of each one of the features available to find scope to work on. Found few features like Sales, Profit, Quantity and Discount and checked for the relationship between these features by plotting the graphs. Found the impact on the Sales feature with the different Regions and sub-regions. Later found outliers in the data and removed them as a part of outlier treatment. Compared the skewness and Kurtosis of both the Z-Score and IQR Outlier treatment respectively. As part of the analysis, few observations: Maximum sales and profits are in Technology, Minimum profits are in Furniture, Sales and Profit are moderately correlated, California has highest deals. 
