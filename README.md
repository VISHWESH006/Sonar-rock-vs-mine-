# Sonar Rock vs. Mine Classification
  This project uses a machine learning model to classify sonar signals as either a rock (R) or a mine (M). The model is built using a Logistic Regression algorithm   from the Scikit-learn library.

# Project Overview
  The script performs the following steps:
  
  Data Loading: Loads the sonar dataset from the sonar.csv file.
  
  Data Preprocessing: The data is analyzed and prepared for training.
  
  Train-Test Split: The dataset is split into training (90%) and testing (10%) sets.
  
  Model Training: A Logistic Regression model is trained on the training data.
  
  Model Evaluation: The model's accuracy is evaluated on both the training and test data.
  
  Prediction: A predictive system is built to classify new, unseen sonar data.

# Dataset
The project uses the "Sonar, Mines vs. Rocks" dataset, which should be available in a file named sonar.csv. This dataset contains 208 rows and 61 columns. The first 60 columns are numerical features representing the energy in different frequency bands, and the 61st column is the label ('R' for Rock or 'M' for Mine).

# Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

# Prerequisites
   Python 3.x

    pip (Python package installer)

# Installation
Clone the repository:

    git clone [https://github.com/VISHWESH006/Sonar-rock-vs-mine.git]
    cd Sonar-rock-vs-mine

# Install the required packages:

    pip install -r requirements.txt

# Usage
To run the project, you can execute the cells in the Sonar.ipynb Jupyter Notebook sequentially. Make sure the sonar.csv dataset file is in the same directory as the notebook.

The notebook will guide you through the data loading, training, and evaluation process. At the end of the notebook, you can input new sonar data to get a prediction.

# Model Performance
The trained Logistic Regression model achieves the following accuracy:

    Training Data Accuracy: ~85.5%

    Test Data Accuracy: ~71.4%
