# Artificial Intelligence — Labs

This repository contains **Jupyter notebooks** for laboratory exercises in the **Artificial Intelligence Course** at **UTM (Technical University of Moldova)**. It focuses on **practical implementations of machine learning models**, including data preprocessing, model training, model evaluation, and data visualization. The notebooks cover **supervised and unsupervised learning techniques** and aim to support **hands-on learning and experimentation in AI**.

## Lab 1 — Linear Regression

- Goal: Learn how to build and evaluate a simple linear regression model to predict customer spending.
- Contents (summary):
    - Data preprocessing: loading CSV, inspecting data (`head()`, `info()`, `describe()`).
    - Data visualization: exploring relationships with `jointplot` and `pairplot`.
    - Model training: splitting data, training a `LinearRegression` model.
    - Model evaluation: predicting test data, calculating MAE, MSE, RMSE, and R².
    - Residual analysis: plotting histograms and interpreting coefficients.

## Lab 2 — Logistic Regression

- Goal: Learn how to build and evaluate a logistic regression model for binary classification.
- Contents (summary):
    - Data preprocessing: loading the dataset, handling missing values, encoding labels, and feature scaling.
    - Exploratory analysis: examining class distribution and feature relationships.
    - Model training: splitting the dataset, training a `LogisticRegression` model.
    - Model evaluation: calculating accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.
    - Prediction analysis: interpreting classification results and model coefficients.

## Lab 3 — Supervised Machine Learning Classification

- Goal: Learn how to implement and evaluate supervised machine learning classification algorithms.
- Contents (summary):
    - Data preprocessing: loading the dataset, handling missing values, encoding labels, and feature scaling.
    - Exploratory analysis: examining data distribution, feature relationships, and class balance.
    - Model training: splitting the dataset, training classification models using `scikit-learn`.
    - Model evaluation: calculating accuracy, precision, recall, F1-score, classification report, and confusion matrix.
    - Prediction analysis: testing models with new data and comparing classification results.

## Lab 4 — Unsupervised Machine Learning Clustering

- Goal: Learn how to build and evaluate unsupervised machine learning clustering algorithms.
- Contents (summary):
    - Data preprocessing: loading the dataset, handling missing values, and feature scaling.
    - Exploratory analysis: examining data distribution and feature relationships.
    - Model training: implementing clustering algorithms using `scikit-learn`.
    - Clustering algorithms implementation: applying different clustering techniques and analyzing generated clusters.
    - Model evaluation: calculating clustering performance using metrics such as silhouette score and visualizing results.
    - Cluster analysis: interpreting obtained groups and comparing clustering methods.

## Lab 5 — Artificial Neural Network

- Goal: Learn how to create and evaluate an artificial neural network using Dense layers for binary classification.
- Contents (summary):
    - Data preprocessing: loading the dataset, handling missing values, encoding labels, and feature scaling.
    - Exploratory analysis: examining data distribution and feature relationships.
    - Model creation: building an artificial neural network using Dense layers with `TensorFlow/Keras`.
    - Model training: compiling, training, and validating the neural network model.
    - Model evaluation: analyzing accuracy, loss, confusion matrix, and classification results.
    - Model optimization: improving the neural network using class weights, additional layers, BatchNormalization, and Dropout.
    - Prediction analysis: interpreting classification results and evaluating the improved model.

## Lab 6 — Convolutional Neural Network

- Goal: Learn how to create and evaluate a convolutional neural network for image classification.
- Contents (summary):
    - Data preprocessing: loading image datasets, decoding images, data augmentation, and preparing training data.
    - Exploratory analysis: visualizing images and analyzing dataset classes.
    - Model creation: building a CNN model using convolutional, pooling, and Dense layers.
    - Model training: compiling, training, and validating the convolutional neural network.
    - Model evaluation: analyzing classification performance and model results.
    - Model comparison: comparing CNN performance with pretrained architectures such as ResNet and Inception.
    - Optimization analysis: improving the CNN model using techniques such as Dropout and BatchNormalization.

## Lab 7 — Deep Learning Models

- Goal: Learn how to create and evaluate deep learning models for image recognition and sequence processing.
- Contents (summary):
    - Environment setup: configuring Google Colab and preparing the deep learning environment.
    - Data preprocessing: preparing image and sequential data for neural network models.
    - CNN implementation: creating and training convolutional neural networks for object and person recognition.
    - RNN implementation: building recurrent neural networks using SimpleRNN, LSTM, and GRU architectures.
    - Model training: optimizing, validating, and testing deep learning models.
    - Model evaluation: analyzing prediction results and comparing different neural network architectures.

## Installation

1. **Clone the repository**

```bash
  git clone https://github.com/Constantin-Stamate/artificial-intelligence-practice
```

2. **Navigate to the project folder**

```bash
  cd artificial-intelligence-practice
```

3. **Start Jupyter Notebook**

```bash
  # jupyter notebook
```

4. **Open the desired notebook**

```bash
  # In the browser that opens, navigate to the 'notebooks' subfolder
  # and open the desired .ipynb file
```

5. **Run the notebook cells**

```bash
  # Run the cells using Shift + Enter
```

## Resources

For guidance and references, you can check:

- [Scikit-learn documentation](https://scikit-learn.org/stable/documentation.html) — for machine learning models in Python  
- [Pandas documentation](https://pandas.pydata.org/docs/) — for data manipulation and preprocessing  
- [Matplotlib documentation](https://matplotlib.org/stable/contents.html) — for data visualization  

## Technologies

- Notebook: Jupyter Notebook
- Editor: Visual Studio Code

## Author

This project was developed as part of the **Artificial Intelligence Course** at **UTM (Technical University of Moldova)**, focusing on the study and implementation of machine learning algorithms.

- GitHub: [Constantin-Stamate](https://github.com/Constantin-Stamate)
- Email: constantinstamate.r@gmail.com