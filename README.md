# K-NN-Enhancement
Assignment of the course Machine Learning I (BSc in Artificial Intelligence and Data Science 2nd year, 2nd semester)

## A little context
### Goal of the work
The aim of this work was:
* Understand how a selected Machine Learning (ML) algorithm works in detail, both
theoretically and empirically;
* Understand how benchmarking of ML algorithms is carried out;
* Understand the difference between ML research and the use of ML to solve a specific
application.


### Vulnerabilities of the algorithm
The following two vulnerabilities stood out as study objects:
* Outliers: once it calculates distances between data points
* Overfitting: with a small K, the algorithm becomes sensitive to noise and outliers in the training data, leading to poor generalization on unseen data
#### Solution Ideas - Bagging:
* Outliers: use distance metrics that are less sensitive to outliers
* Overfitting: by using different subsets of features, each model focuses on different aspects of the data, reducing the risk of overfitting to specify features or relationships

### The notebook
It is composed by 3 main parts:
* K-NN classes
* Statistics
* Train functions

To begin the dataset was splitted the dataset and was used only the numeric features.
So that the user could experience the differnt model separatley, he can run each one individually.
1, 2 or 3, which one is associated with a different model: base case, bagging (different distances) and different features, respectively.
