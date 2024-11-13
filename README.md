Self-Organizing Map (SOM) and Artificial Neural Network (ANN) Analysis
Welcome to the SOM and ANN Combined Analysis project! This repository demonstrates how to leverage the power of Self-Organizing Maps (SOM) for unsupervised learning and anomaly detection, followed by a Supervised Artificial Neural Network (ANN) to make predictions. The combination of SOM and ANN provides a robust framework for uncovering hidden patterns and making accurate predictions.

🚀 Project Overview
The goal of this project is to:

Use Self-Organizing Maps (SOM) to detect anomalies or potential frauds in a dataset of credit card applications.
Utilize the detected frauds as labels for training a Supervised Artificial Neural Network (ANN).
Perform predictions to classify new data points and evaluate the model's performance.
📂 Dataset
The dataset used in this project is Credit_Card_Applications.csv, which contains various features of credit card applications and a binary target column indicating approval status (0 for rejected, 1 for approved).

🛠️ Project Workflow
Data Preprocessing:

Load the dataset and separate features (X) and labels (y).
Scale the features using MinMaxScaler for optimal performance of SOM and ANN.
Training the SOM:

Initialize a 10x10 SOM grid using the MiniSom library.
Train the SOM using the preprocessed data to identify clusters and detect anomalies.
Visualizing the SOM Results:

Generate a heatmap of the SOM's distance map.
Highlight anomalies using markers based on the approval status of applications.
Building the ANN:

Use the frauds detected by the SOM as the labeled dataset for training the ANN.
Construct a neural network using Keras with input, hidden, and output layers.
Compile and train the ANN using the labeled data.
Evaluating the Model:

Evaluate the performance of the ANN using metrics such as accuracy, precision, and recall.
Make predictions on new data and visualize the results.
📊 Results
The combined approach of SOM for anomaly detection followed by ANN for classification achieved impressive results. The project successfully detected anomalies and used them to train a predictive model, showcasing the effectiveness of hybrid machine learning techniques.
