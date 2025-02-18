# Employee Salary Prediction using Linear Regression Model (using Machine Learning and Streamlit)

  # Description:

  This project implements a simple linear regression model to predict employee salaries based on their years of experience.
  The dataset contains two features: years of experience and salary. The goal of this project is to train a machine 
  learning model that can predict an individual's salary given their years of experience.

  # Insights:

  # What I Build:

  - Used a Simple Linear Regression model to predict salary based on years of experience. The dataset ('Salary_Data.csv') is split into training and test sets, 
    and the model is trained on the training set. The performance of the model is visualized on both the training and test sets using scatter plots and regression 
    lines.
  - Created Numerical Data Processing Pipeline
  - Model Building Pipeline
  - Prediction Pipeline
  - Trained a Linear Regression model to understand the correlation between experience and salary trends.
  - Designed interactive visualizations to make results both engaging and informative.
  - Deployed the model as a sleek, web-based tool using Streamlit for real-time predictions.

  # Key Features:

  - Load and preprocess data from CSV
  - Train a linear regression model
  - Evaluate model performance using R² score
  - Visualize the training and test set results
  - Make predictions for specific years of experience (e.g., 12 and 20 years)
  - Save the trained model using Python's pickle library for later use

  # Technologies Used:
  - Python: Numpy, Pandas, Matplotlib, Pickle, scikit-learn
  - Deployment: Streamlit for an interactive UI and Pickle for efficient model handling

  # Dataset:
  - The dataset Salary_Data.csv should have two columns:
    1) YearsExperience - Number of years of work experience.
    2) Salary - Salary in dollars.
  - Place this dataset in the root directory of the project.

  # Project Structure:
           salary-prediction/
           │
           ├── Salary_Data.csv             # Dataset file
           ├── Salary_pred.py              # Python script for salary prediction
           ├── linear_regression_model.pkl # Pickled model after training
           ├── Salapp.py                   # streamlit app for prediction
           ├── README.md                   # Project documentation



  - The script will:

     * Train the linear regression model on 80% of the data.
     * Evaluate it on 20% of the test data.
     * Print a comparison of actual and predicted salaries.
     * Show visualizations for both training and test sets.
     * Save the trained model as linear_regression_model.pkl using pickle.
     * You can also see salary predictions for 12 and 20 years of experience as an example.

 # Results:
 - Once the script is executed, it will print the following details:

     * Comparison of actual vs predicted salaries for the test set 
     * Visualizations for both training and test sets
     * Predicted salaries for 12 and 20 years of experience
     * Model performance in terms of R² and MSE
       
This project highlights how machine learning can turn raw data into actionable insights while offering practical tools for everyday use. By analyzing these metrics, we can evaluate the accuracy and precision of the model's predictions and make informed decisions about its effectiveness in real-world scenarios.

![Output_Salary](https://github.com/user-attachments/assets/06f3838d-0c32-4735-af31-a63efb971845)


