# msbd-5001-kaggle
1.language
The programming language I use is python.

2.packages

pandas,numpy,seaborn,sklearn.datasets(make_classification)，keras.models(Sequential),  keras.layers(Dense)(Dropout)
I import them in jupyter notebook:

import pandas as pd
import numpy as np
from sklearn.datasets import make_classification
TrainData = pd.read_csv("5001train.csv")
TestData  = pd.read_csv("5001test.csv")
from pandas.core.frame import DataFrame
from keras.models import Sequential
from keras.layers import Dense
from keras.layers import Dropout
import numpy

3.Model

Two layers full connected Neural Network 

4. Method

Real time is used as label to predict time 
