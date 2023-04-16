# Iris-Dataset-Classification
## Machine Learning Classififcation of the Iris Dataset
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

The columns in this dataset are:
- Id
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm
- Species

### EDA 
- The Iris species are evenly distributed ( equal number of eac species)
- There is a positive correlation between the Sepal lenth and Petal Length
- There is also a positive correlation between the Sepal lenth and Petal width
- There is also positive correlation between the Petal width and Petal Length
- There is a negative correlation between te Sepal width and all other features

### MODEL CREATION AND EVALUATION
- Before the model was created, the dataset was splitted into Train and test with a percentage of 30% for the test data and randomization of 42.
- Differnet classification algorithms was used. i.e Logistic Regression, Decision Trees, Random forest, Gradient boosting and K Nearest Neighbors Classifier. Each of the model performed exellently well both in the training and the testing phase. The Logostic Reression has the lowest with an accuracy of 91% on the test data. 
