# COVID 19 - Reopening Counties Safely
<p align="center">
  <img width="auto" height="auto" src="https://californiahealthline.org/wp-content/uploads/sites/3/2020/06/bernardcovid19-01.jpg?w=1024">
</p>

# Project Description

Given its current circumstances, should a county reopen to prevent a second outbreak of COVID 19? We will answer this question by identifying similar counties, which can be referred to when deciding whether a county should expect a spike in infection rates if it were to reopen given the current circumstances.

To reach a conclusion, we will use Ensemble Models to find the optimal algorithm; run a Logistic Regression Model to identify what factors affect infection rates the most; and lastly create a kNN recommender system to identify similar counties in order to predict whether a spike in infection rates will occur or not.italicized text


## Steps

 1. Data Cleaning
 2. Data Merging
 3. Ensemble Models
 4. Logistic Regression
 5. kNN Recommender System

## Requirements

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**Integrated Development Environment (IDE).** Any IDE that can be used to view, edit, and run Python code, such as:
- [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
- [Jupyter Notebook](https://jupyter.org/).


### Packages 
Install the following packages in Python prior to running the code.
```python
# Importing modules
import pandas as pd
import numpy as np
from termcolor import colored as cl
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import precision_score, classification_report, confusion_matrix, roc_auc_score, log_loss, jaccard_similarity_score as jss 
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.metrics import roc_curve

%matplotlib inline

from google.colab import drive
```

If using Google Colab, import drive.mount('/content/drive') and follow instructions in the output to authorize access to Google Drive in order to obtain directories.


## Launch
Download the Python File *COVID_19_Reopening.ipynb* and open it in the IDE. Download and import the dataset *wine.csv*. 


## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)
Kassie Xie
Jack Taylor


## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The Dataset used was provided by the CDC, New York Times, and John Hopkins University.
