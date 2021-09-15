# Machine-Learning-with-Python-Cookbook-Practical-Solutions-from-Preprocessing-to-Deep-Learning

##  Some popular sample datasets in scikit-learn
   #### load_boston
         Contains 503 observations on Boston housing prices. It is a good dataset for exploring regression algorithms.
   #### load_iris
         Contains 150 observations on the measurements of Iris flowers. It is a good data‐set for exploring classification algorithms.
   #### load_digits
        Contains 1,797 observations from images of handwritten digits. It is a good data‐set for teaching image classification.

## scikit-learn offers many methods for creating simulated data. Of those,  three methods are particularly useful.
 1. When we want a dataset designed to be used with linear regression,make_regression is a good choice:
     #### from sklearn.datasets import make_regression
 2. If we are interested in creating a simulated dataset for classification, we can use make_classification:
     #### from sklearn.datasets import make_classification
 3. Finally, if we want a dataset designed to work well with clustering techniques, scikitlearn offers make_blob
     #### from sklearn.datasets import make_blobs
