# Lung and Colon Cancer Detection
This project aims to detect lung and colon cancer from histopathological images using deep learning techniques. It includes a deep neural network model, data preprocessing, training, evaluation, and model saving. The code is structured to provide a comprehensive solution for cancer detection.

# Table of Contents
Introduction
Project Structure
Getting Started
Data Preparation
Model Architecture
Training
Evaluation
Saving the Model

# Introduction
Lung and colon cancer detection is a critical task in the field of medical image analysis. Early and accurate diagnosis can significantly improve patient outcomes. This project uses deep learning to classify histopathological images as either cancerous or benign, contributing to the early detection of these cancers.

# Project Structure
data: This directory contains the dataset of histopathological images. src: This directory contains the Python code for data preprocessing, model creation, training, and evaluation. saved_models: This directory is where trained models and their weights are saved. requirements.txt: A list of Python dependencies for reproducing the environment.

# Getting Started
To get started with this project, follow these steps: Clone this repository to your local machine. Install the required dependencies by running pip install -r requirements.txt. Organize your dataset into the data directory, following the structure provided in the project. Run the code for data preprocessing and model training, following the instructions in the source code. Evaluate the model's performance on the test dataset. Save the trained model for future use.

# Data Preparation
Before training the model, ensure that your dataset is organized correctly in the data directory. The dataset should be split into train, validation, and test sets if available. The code for data preprocessing will load and augment the images for training.

# Model Architecture
The deep neural network model used for cancer detection consists of several convolutional and pooling layers. The model architecture is defined in the source code within the create_model function.

# Training
To train the model, execute the training script provided in the src directory. You can adjust hyperparameters such as batch size, learning rate, and the number of epochs to fine-tune the model's performance.

# Evaluation
After training, the model's performance can be evaluated using the validation and test datasets. The code generates accuracy, loss, and a confusion matrix to assess the model's effectiveness in cancer detection.

# Visualization
![dataset](https://github.com/adi271001/DL-Simplified/assets/67856422/ddeec067-df03-49aa-bd24-5071a69332b3)
![training](https://github.com/adi271001/DL-Simplified/assets/67856422/d8d4ff4b-40f0-4a9a-99f4-25086ab5990e)
![plot_training_testing](https://github.com/adi271001/DL-Simplified/assets/67856422/c1f7d305-ad94-45c4-8fc0-4d4e66ca441b)
![accuracy](https://github.com/adi271001/DL-Simplified/assets/67856422/9298bfe0-890b-4321-9b7d-2f2d156c0637)
![classification_report](https://github.com/adi271001/DL-Simplified/assets/67856422/f6df8216-eb6b-4422-947f-3dc0ce8fd09a)
![confusion_matrix](https://github.com/adi271001/DL-Simplified/assets/67856422/649c373d-64ff-417a-9bd0-04739cc962e2)


# Results 
The model achieved an accuracy of 99.6399, Graphs are attached  which shows that the model is neither overfitted nor underfitted

# Saving the Model
The trained model and its weights can be saved for future use. You can easily save both the model architecture and the learned weights using the provided code. The saved model can then be loaded and used for making predictions on new data.
