# Salary_Prediction_Project

Below is My Live Application Link

--> https://salarypredictionproject-gf2edso5cd7nwuvl9wy5be.streamlit.app/

💰 Employee Salary Prediction Web Application

Overview

This project is a minimal, fully functional web application built with Streamlit that deploys a pre-trained Linear Regression model. The application provides an interactive interface for users to input key employee metrics and receive a real-time prediction of their potential annual salary.

This serves as an excellent demonstration of the MLOps process, specifically how to serialize a trained model using pickle and deploy it as a simple, user-friendly web service.

Key Features

Interactive Input: Users can easily adjust three key features—Years of Experience, Education Level, and Age—using interactive sliders and dropdown menus in the sidebar.

Real-Time Prediction: The model processes the input data instantly upon button click and displays the predicted salary in USD.

Minimalistic UI: Built with Streamlit for a clean, responsive, and easy-to-use interface.

Model Deployment: Demonstrates the successful loading and utilization of a serialized scikit-learn model (.pkl file) within a production environment.

Model and Data

The underlying predictive engine is a Linear Regression model trained on a simulated dataset.

Features Used:

Feature

Type

Description

Experience

Numerical (Years)

The number of years the employee has worked in the field.

Education_Level

Categorical/Encoded

Encoded as 1 (High School), 2 (Bachelor's), or 3 (Master's/PhD).

Age

Numerical (Years)

The employee's current age.

The model predicts the continuous numerical output: Salary (USD).

Project Structure

.
├── Linear_Regression.pkl   # The serialized, trained model
├── linear_regression_dataset.csv # (Optional) Dataset used for training
├── app.py                  # The main Streamlit web application file
└── requirements.txt        # List of necessary Python dependencies


🚀 Getting Started (Local Setup)

Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites

You need Python 3.8+ installed on your system.

1. Clone the Repository

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name


2. Install Dependencies

All required packages are listed in requirements.txt.

pip install -r requirements.txt


3. Run the Streamlit Application

Execute the main application file using the Streamlit CLI:

streamlit run app.py


The application will automatically open in your default web browser (usually at http://localhost:8501).

Dependencies

The project relies on the following Python libraries, as detailed in requirements.txt:

streamlit: For building the web application interface.

scikit-learn: For loading and running the Linear Regression model.

pandas: For handling data input structures.

numpy: A core dependency for numerical operations.

Contributing

Feel free to open issues or submit pull requests to improve the application, add visualizations, or explore different model types!
