# Wine Type Classification Project

## Overview
This project aims to predict the type/category of wine using machine learning algorithms. Two models were implemented and evaluated: **Random Forest** and **Support Vector Classifier (SVC)**. The models achieved perfect performance metrics (accuracy, precision, recall, and AUC of 1.0), suggesting exceptional generalization on the dataset used. Below are the details of the project, including setup, methodology, and results.

---

## Dataset
The dataset used is the **Wine Dataset**, which contains 13 features describing chemical properties of wines, along with a target variable indicating the wine class (3 possible types). Features include:
- Alcohol
- Malic acid
- Ash
- Alcalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

**Target Variable**: Wine class (0, 1, 2).

---

## Requirements

   - Python 3.8+
   
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import confusion_matrix
from sklearn.compose import ColumnTransformer
from sklearn.pipeline import Pipeline
from sklearn.impute import SimpleImputer
from sklearn.preprocessing import StandardScaler, OrdinalEncoder
from sklearn.svm import SVC
from sklearn.ensemble import RandomForestClassifier
import joblib
from sklearn.metrics import roc_curve, roc_auc_score
import seaborn as sns
