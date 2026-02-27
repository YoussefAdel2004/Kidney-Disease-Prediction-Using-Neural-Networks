# Kidney-Disease-Prediction-Using-Neural-Networks
This project implements a neural network model from scratch to predict the presence of kidney disease using patient medical records. It is a binary classification task using tabular data that contains both numerical and categorical features
# Problem Definition
Task Type
Binary Classification
Objective
Predict whether a patient has kidney disease:

1 → Disease present

0 → No disease

Input Features

Age

Blood pressure

Blood test results

Other clinical attributes

Mix of numeric and categorical variables

Why Neural Networks?

Capture complex non-linear relationships

Handle mixed data types after preprocessing

Perform well on medical diagnosis tasks

# Dataset

Source: Kaggle – Kidney Function Health Dataset

Format: CSV

Loaded using raw string paths to avoid Windows path issues

# Exploratory Data Analysis (EDA)

Descriptive statistics (mean, std, min, max)

Feature distribution plots

Correlation heatmap

Missing value analysis

Outlier detection

# Data Cleaning

Median imputation for numeric features

Mode imputation for categorical features

Outlier handling using IQR method

Duplicate removal

Data type standardization

# Data Preprocessing

Label Encoding for categorical variables

Min-Max normalization (0–1 scaling)

Dataset split:

60% Training

20% Validation

20% Testing

# Neural Network Architecture
Input Layer (11)
→ Hidden Layer (16, ReLU)
→ Output Layer (1, Sigmoid)

# Training Details

Loss Function: Binary Cross-Entropy + L2 Regularization

Optimizer: Gradient Descent

Manual forward & backpropagation implementation

Training & validation loss tracking

# Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

# Experiments & Tuning

Hidden units: 8, 16, 32

Learning rates: 1e-3, 1e-4, 1e-5

Activation functions: ReLU, Tanh

# Visualizations

Training vs validation loss curves

Accuracy curves

Confusion matrix

Feature distributions (before & after cleaning)

Correlation heatmap

# Technologies

Python 3

NumPy

Pandas

Matplotlib

Scikit-learn
