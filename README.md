# Breast_Cancer_Decision_Tree_Classifier
## This code helps you to classify malignant and benign tumors using Decision Tree Classifier.

## How to run the script
You can run the BreastCancer.ipynb using a Jupyter Notebook and BreastCancer.py using python IDE(integrated development environment) like spyder. To install Jupyter Notebook and spyder on your system, you will need to download the Anaconda installer. This script is written in Python 3, so you will need the Python 3.x version of the installer. After downloading and installing Anaconda, you will find the Jupyter Notebook and spyder by opening Anaconda Navigator.

## Dataset
Dataset is taken from ( https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic) ) 
It contains 32 Attributes and 569 Instances

* id : ID number
* diagnosis : The diagnosis of breast tissues (M = malignant, B = benign)
* radius_mean : mean of distances from center to points on the perimeter
* texture_mean : standard deviation of gray-scale values
peri*meter_mean : mean size of the core tumor
* area_mean
* smoothness_mean : mean of local variation in radius lengths
* compactness_mean : mean of perimeter^2 / area - 1.0
* concavity_mean : mean of severity of concave portions of the contour
* concave points_mean : mean for number of concave portions of the contour
* symmetry_mean
* fractal_dimension_mean : mean for "coastline approximation" - 1
* radius_se : standard error for the mean of distances from center to points on the perimeter
* texture_se : standard error for standard deviation of gray-scale values
* perimeter_se
* area_se
* smoothness_se : standard error for local variation in radius lengths
* compactness_se : standard error for perimeter^2 / area - 1.0
* concavity_se : standard error for severity of concave portions of the contour
* concave points_se : standard error for number of concave portions of the contour
* symmetry_se
* fractal_dimension_se : standard error for "coastline approximation" - 1
* radius_worst : "worst" or largest mean value for mean of distances from center to points on the perimeter
* texture_worst : "worst" or largest mean value for standard deviation of gray-scale values
* perimeter_worst
* area_worst
* smoothness_worst : "worst" or largest mean value for local variation in radius lengths
* compactness_worst : "worst" or largest mean value for perimeter^2 / area - 1.0
* concavity_worst : "worst" or largest mean value for severity of concave portions of the contour
* concave points_worst : "worst" or largest mean value for number of concave portions of the contour
* symmetry_worst
* fractal_dimension_worst : "worst" or largest mean value for "coastline approximation" - 1

## Reference
* Decision Tree Doccument : https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
* StanderedScalar : https://stackoverflow.com/questions/40758562/can-anyone-explain-me-standardscaler
* LabelEncoder : https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
* Accuracy_score : https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html
