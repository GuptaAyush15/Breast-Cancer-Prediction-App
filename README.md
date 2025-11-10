Breast Cancer Prediction App
This project implements an interactive Breast Cancer Prediction App using machine learning and IPyWidgets in Google Colab. The app allows users to input several features of a tumor (Mean Radius, Mean Texture, Mean Perimeter, Mean Area, and Mean Smoothness) via sliders and then predicts whether the tumor is Malignant or Benign.

Project Overview
This application uses a RandomForestClassifier model trained on a subset of the Breast Cancer Wisconsin (Diagnostic) dataset. The model is designed to classify tumors as either malignant (cancerous) or benign (non-cancerous) based on five key characteristics. The interactive interface is built with IPyWidgets, making it easy to test different input values and observe predictions directly within the Colab environment.

Features
Interactive Sliders: Adjust tumor characteristics (Mean Radius, Mean Texture, Mean Perimeter, Mean Area, Mean Smoothness).
Real-time Prediction: Get an instant prediction (Malignant/Benign) with confidence score upon clicking the 'Predict' button.
Machine Learning Model: Utilizes a RandomForestClassifier for robust predictions.
Setup and Installation
Open in Google Colab: Open this notebook in Google Colab.
Install IPyWidgets: Ensure ipywidgets is installed. The first cell in the notebook handles this automatically:
!pip install ipywidgets --quiet
How to Run the App
Execute All Cells: Run all code cells in the notebook sequentially. This will:
Install necessary libraries.
Load the Breast Cancer dataset.
Train the RandomForestClassifier model.
Create and display the IPyWidgets interactive interface.
Interact with Sliders: Once the widgets are displayed, adjust the sliders to change the values for 'Mean Radius', 'Mean Texture', 'Mean Perimeter', 'Mean Area', and 'Mean Smoothness'.
Get Prediction: Click the 'Predict' button to see the model's prediction (Malignant or Benign) and its confidence level.
Technologies Used
Python
pandas: For data manipulation.
<img width="299" height="205" alt="Image" src="https://github.com/user-attachments/assets/566a4f1d-9b39-4438-9039-4d12f18c6de7" />
