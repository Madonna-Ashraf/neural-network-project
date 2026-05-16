# neural-network-project
# Diabetes Prediction Using MLP
## Problem Description
This project uses a Multilayer Perceptron (MLP) neural network to predict whether a patient is diabetic or non-diabetic using medical features such as glucose, BMI, blood pressure, insulin, and age.
## Dataset Link
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
## Results
| Experiment | Learning Rate | Dropout | Test Accuracy |
|------------|---------------|---------|---------------|
|Experiment 1|     0.0025    |   0.3   |      ~70%     |
|Experiment 2|     0.001     |   0.3   |      ~68%     |
|Experiment 2|     0.005     |   0.3   |      ~74%     |
## Instructions for Running the Project
1)Download the Project
2)Install Required Libraries
```
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
import torch
import torch.nn as nn
import torch.optim as optim
import matplotlib.pyplot as plt
```
