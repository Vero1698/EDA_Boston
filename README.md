# EDA_Boston
## Step 1:
We start to import all libraries that we will use for dataset of Boston

from sklearn import datasets
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

## Step 2:
Function that get the target name of the file and return the name of the values

def bostons(value):
    boston = boston_dat.target_names[value]
    return boston

boston_function = lambda x: boston_dat.target_names[x]
