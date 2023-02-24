CA 04 - README
Purpose: The purpose of this program, file CA 03, is to present 4 different types of decision classifiers on a census data set.
The classifiers explored are Random Tree Classifier, ADA Boost Classifier, Gradient Boosting Classifier, and Extreme Gradient Boosting Classifier.

The four classifiers are ran to compare accuracy and the AUC.
The libraries necessary to conduct this program and be able to run the code: Pandas Sklearn Os Matplotlib Numpy Counter from collections What versions of various software / libraries are you using:
Python 3 (ipykernel) numpy=1.22.1 pandas== 1.4.0 matplotlib= 3.5.1
The dataset used for this program and its source: https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true"”
Code Acknowledgements: CHATGPT
Upload the Github url onto the environment and make sure the necessary libraries and modules are installed:
import matplotlib.pyplot as plt
import numpy
import pandas
import seaborn
from sklearn.metrics import confusion_matrix
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score
from sklearn.metrics import classification_report
import sklearn.datasets as datasets
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import roc_auc_score