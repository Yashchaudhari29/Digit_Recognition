# Digit_Recognition
This project focuses on implementing a machine learning model to recognize handwritten digits. It utilizes the Support Vector Machine (SVM) algorithm, a powerful classification technique, to accurately classify digits ranging from 0 to 9.

### Insatll The Libraries 
```
pip install scikit-learn
pip install matplotlib
pip install pandas
```
### Import's
```
from sklearn.datasets import load_digits
from sklearn.svm import SVC
import pandas as pd
from matplotlib import pyplot as plt
from sklearn.model_selection import train_test_split
import seaborn as sn
```
### Choose diffrent kernals for diffrent accuracy
```
model = SVC(kernel='rbf')
'linear', 'poly', 'rbf', 'sigmoid', 'precomputed'
```
