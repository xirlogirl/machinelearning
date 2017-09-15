# Applied Machine Learning in Python Week 1

## Introduction to sklearn, pandas and a k-NN model

In these files I will provide a quick overview of the concepts covered in this course. As Coursera does not want students to post code from the assignments etc. I will describe some of the techniques that were taught in the course with limited code examples.

This week provided an introduction to scikit-learn, use of pandas and matplotlib for basic tasks.
The lectures focussed on an example where a model was trained to classify fruit based on its height, width, mass and color.
Simple tasks such as creating a scatter matrix to view possible correlations between features, sklearn train-test split were demonstrated. 

A k-Nearest Neighbours classifer was used to predict fruit class with different values for k (from 1 to 20).
Decision boundaries were shown for each case.

The assignment for this week worked with the breast cancer dataset, which is included in sklearn.datasets.
Again, exploratory tasks with Pandas were asked - size of the dataset, count numbers in each class, use of iloc for a dataframe. Tasks done with sklearn include train_test_split, use of a KNeighborsClassifier to predict labels for the test data in the breast cancer dataset and measurement of the score using knn.score.

Finally, a plot was made with matplotlib to show the scores of training and test sets for malignant and benign tumor classification.

