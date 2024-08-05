# Machine Learning Projects

This repository contains the Jupyter notebooks for various machine learning projects I implemented during my studies.

## Projects

### Project 1: Getting Started with Machine Learning

#### Overview
In this project, I implemented two machine learning algorithms, K-Nearest Neighbour (KNN) and Decision Trees (DTs), and compared their performance on two health-related datasets.

#### Files
- `assignment1_group-25.ipynb`: Jupyter notebook containing the implementation, experiments, and results for the project.

#### Summary
I implemented and tested KNN and DT on the Hepatitis and Diabetic Retinopathy Debrecen datasets. KNN showed slightly better accuracy than DT depending on the dataset used. Various parameters and cost functions were tested for both models.

### Project 2: Logistic Regression and Multiclass Classification

#### Overview
This project focused on implementing logistic regression for binary classification and a multiclass classifier. The performance was tested on the IMDB Reviews dataset and the 20 Newsgroups dataset.

#### Files
- `Logistic Regression.ipynb`: Jupyter notebook containing the implementation of logistic regression and multiclass classification, along with the experiments and results.

#### Summary
Logistic regression outperformed KNN on the IMDB dataset, showing higher accuracy and faster training times. The multiclass classifier showed marginally better performance on the 20 Newsgroups dataset compared to KNN.

### Project 3: Classification of Image Data Using Neural Networks

#### Overview
In this project, I implemented a Multilayer Perceptron (MLP) from scratch to classify image data from the Fashion-MNIST dataset. Different activation functions and network architectures were tested to optimize performance.

#### Files
- `Neural Network.ipynb`: Jupyter notebook containing the implementation of MLP, experiments with different activation functions and network depths, and the results.

#### Summary
My best model achieved an accuracy of 82.46% with a neural network of two hidden layers using the tanh activation function. Experiments showed that increasing the number of hidden layers and using certain activation functions improved accuracy.

## How to Run

1. Ensure you have the necessary dependencies installed. You can create a virtual environment and install the dependencies using:
    ```sh
    python -m venv env
    source env/bin/activate
    pip install -r requirements.txt
    ```

2. Open the Jupyter notebooks in your preferred environment (e.g., Jupyter Lab, Jupyter Notebook):
    ```sh
    jupyter notebook
    ```

3. Navigate to the notebook you want to explore and run the cells to see the implementation and results.

