# Artificial Neural Network (ANN) – Iris Classification

A beginner-level Deep Learning project implementing an **Artificial Neural Network (ANN)** for classification using the **Iris dataset**.

This notebook was created as part of my learning journey in Deep Learning while following a YouTube tutorial. The main goal was to understand the fundamentals of neural networks, data preprocessing, classification, and TensorFlow/Keras.

> **Learning Project:** This repository is primarily focused on learning and practicing Artificial Neural Network concepts rather than presenting an original research project.

---

## 📌 Project Overview

The project uses the classic **Iris dataset** to classify iris flowers into three different species based on their physical measurements.

The dataset contains the following input features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable is the **Species** of the flower.

The three classes are:

* `Iris-setosa`
* `Iris-versicolor`
* `Iris-virginica`

The notebook also checks the class distribution, which contains **50 samples from each class**.

---

## 🎯 Objective

The main objectives of this project were to:

* Understand the basic workflow of a Deep Learning classification problem
* Load and explore a dataset using Pandas
* Encode categorical target labels
* Split the dataset into training and testing sets
* Standardize numerical features
* Understand the Perceptron as a simple linear classifier
* Learn the basic structure of an Artificial Neural Network
* Work with TensorFlow and Keras
* Understand concepts such as Dense layers, Dropout and one-hot encoding
* Evaluate classification model performance

---


---

## 🛠️ Technologies & Libraries

### Programming Language

* Python

### Libraries

* **NumPy** – Numerical operations
* **Pandas** – Data loading and manipulation
* **Scikit-learn** – Data preprocessing, splitting and evaluation
* **TensorFlow** – Deep Learning framework
* **Keras** – Neural Network API
* **Jupyter Notebook** – Development environment

## The notebook imports TensorFlow/Keras along with Scikit-learn utilities such as `train_test_split`, `LabelEncoder`, `StandardScaler`, `Perceptron`, and classification metrics.

## 📊 Dataset

The project uses the **Iris dataset** .

The dataset includes:

| Feature         | Description         |
| --------------- | ------------------- |
| `SepalLengthCm` | Length of the sepal |
| `SepalWidthCm`  | Width of the sepal  |
| `PetalLengthCm` | Length of the petal |
| `PetalWidthCm`  | Width of the petal  |
| `Species`       | Target class        |

The `Id` column is also present in the original dataset.

---


---

## 🧠 Machine Learning & Deep Learning Concepts

During this project, I worked with several important concepts.

### Perceptron

The Scikit-learn `Perceptron` was explored as a simple linear classifier and as a foundation for understanding neural networks.

### Sequential Model

Keras `Sequential` was used as the basic approach for constructing a neural network layer by layer.

### Dense Layers

Dense layers represent fully connected neural-network layers where neurons are connected to neurons in the next layer.

### Dropout

Dropout was explored as a regularization technique that can help reduce overfitting by randomly dropping neurons during training.

### One-Hot Encoding

Keras `to_categorical` was included for converting numerical class labels into one-hot encoded representations.

---

## 📈 Model Evaluation

The notebook includes Scikit-learn tools for evaluating classification performance:

* Accuracy
* Classification Report
* Confusion Matrix

These metrics can be used to understand how well the model performs on the classification task.

---

## 📚 Key Learnings

Through this project, I learned and practiced:

* How to prepare data for a neural network
* Why categorical labels need to be encoded
* How train-test splitting works
* Why feature scaling is important
* Basics of Perceptrons
* Fundamentals of Artificial Neural Networks
* Working with TensorFlow and Keras
* Understanding Dense layers
* The purpose of Dropout
* One-hot encoding for multi-class classification
* Basic classification model evaluation

---

## 🚀 Future Improvements

As I continue learning Deep Learning, I plan to improve this project by:

* Experimenting with different ANN architectures
* Trying different numbers of neurons and hidden layers
* Comparing different activation functions
* Experimenting with different optimizers
* Adding training and validation accuracy/loss plots
* Improving model evaluation
* Comparing ANN performance with traditional ML models
* Deploying the trained model using Streamlit

---

---

## 🎓 Learning Resource

This project was created as part of my Deep Learning learning journey by following the Sheryians AI School YouTube playlist/tutorial by Akarsh Vyas.

The implementation in this repository represents my hands-on practice and understanding of the concepts covered in the tutorial.

---

## 👨‍💻 About

This project is part of my ongoing journey of learning **Data Science, Machine Learning and Deep Learning**.

I am currently building my understanding of neural networks by implementing concepts practically and gradually moving toward more advanced Deep Learning projects.

---

⭐ If you find this repository useful, feel free to explore the notebook and follow my learning journey.
