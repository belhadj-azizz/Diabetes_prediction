# **🧠 Diabetes Prediction Project**
This project focuses on predicting whether a patient is likely to have diabetes based on diagnostic measurements. It showcases a full machine learning workflow — from exploratory data analysis to implementing deep learning models from scratch and with PyTorch.

## **📊 Project Overview**
The goal of this project is to build and compare different models for binary classification on the diabetes dataset. The project demonstrates:
- End-to-end data analysis and preprocessing
- Implementation of machine learning and neural network models from scratch
- Reproduction of neural networks using a deep learning framework (PyTorch)

## **🧠 Methodology**

**1. Exploratory Data Analysis (EDA)**
- Inspected dataset for missing values, distributions, and correlations.
- Visualized key relationships using plots (e.g., glucose vs BMI).

**2. Feature Engineering & Scaling**
- Created relevant features to improve predictive performance.
- Applied normalization/scaling techniques to numerical features.

**3. Model Implementations**
- Logistic Regression (from scratch)
	- Implemented the mathematical formulation manually (sigmoid activation, gradient descent optimization).
	- Served as a baseline model

- Shallow Neural Network (1 hidden layer, from scratch)
	- Built using NumPy.
	- Implemented forward and backward propagation manually.
	- Activation: ReLU (hidden layer), Sigmoid (output layer).
- Deep Neural Network (from scratch)
	- Extended to multiple hidden layers.
	- Implemented full modular structure with parameter initialization, mini-batch gradient descent, and loss computation.
	- Applied implementation knowledge gained from Andrew Ng’s Deep Learning Specialization.
- Deep Neural Network (PyTorch Implementation)
	- Reimplemented the deep neural network using PyTorch for comparison.
	- Learned the syntax and model definition approach from a DataCamp course.
	- Used torch.nn.Module and torch.optim for cleaner architecture and training loop.

## **⚙️ Technologies Used**
	- Languages: Python
	- Libraries: NumPy, Pandas, Matplotlib, PyTorch
	- Environment: Jupyter Notebook

## **📚 Learning Outcomes**
Through this project, I:
- Strengthened my understanding of gradient-based optimization and backpropagation.
- Learned how to build and debug neural networks from scratch using NumPy.
- Gained practical familiarity with PyTorch’s architecture and training pipeline.
- Applied end-to-end data preprocessing and feature engineering for tabular datasets.
- Learned how to analyze results for imbalanced data, going beyond accuracy to focus on recall and other relevant metrics.
- Experimented with and applied different hyperparameter tuning strategies (e.g., learning rate adjustment, number of hidden units, regularization techniques) to improve both accuracy and recall rate.

## **👨‍💻 Author**
#### **Aziz Ben Hadj Fradj**
##### Master’s student in Business Analytics @ MSB
###### Interested in combining Data Science, AI, and Healthcare Innovation


<img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/ef474dce-9800-4984-bbe2-8e53f8ab285e" />
Dataset link: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
