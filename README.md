# Wine Quality Prediction

This project aims to predict wine quality using Machine Learning, specifically employing the Random Forest algorithm. The focus is on accurately classifying wines based on their quality attributes.

## Sample Wine Attributes

For this project, the following sample wine attributes are used:

- **Fixed Acidity**: 7.2
- **Volatile Acidity**: 0.75
- **Citric Acid**: 0.1
- **Residual Sugar**: 5.0
- **Chlorides**: 0.09
- **Free Sulfur Dioxide**: 18
- **Total Sulfur Dioxide**: 88
- **Density**: 0.998
- **pH**: 3.6
- **Sulphates**: 0.5
- **Alcohol**: 8.5

## Importing Necessary Libraries

To begin the project, the following Python libraries are imported:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score
