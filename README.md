# Classification-of-IRIS-DATA-Using-different-Machine-Learning-Algorithms
This program performs machine learning on the Iris dataset, which contains measurements for 150 iris flowers with 4 features each: sepal length, sepal width, petal length, and petal width. The program uses various machine learning algorithms to classify the flowers into their corresponding species: Iris-setosa, Iris-versicolor, and Iris-virginica.

The program first reads in the Iris dataset using pandas and performs some exploratory data analysis, including plotting histograms of the features and a pairwise scatterplot matrix. It then preprocesses the data by replacing the species names with numeric values and splitting the data into training and testing sets using the train_test_split function from scikit-learn.

Next, the program trains and evaluates four different machine learning algorithms: K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), and Random Forest Classifier. It measures the accuracy of each algorithm on the training and testing data and prints out the results.

The program uses scikit-learn's accuracy_score and score functions to evaluate the accuracy of the models. The KNN classifier is used with n_neighbors set to 8, the SVM classifier is used with an RBF kernel and gamma=0.10, and the Random Forest Classifier is used with default parameters.

Overall, the program demonstrates the use of various machine learning algorithms to classify Iris flowers based on their measurements and evaluates their accuracy on the Iris dataset.
