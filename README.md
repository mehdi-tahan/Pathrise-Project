# Pathrise Job Placement Prediction Project
## Overview
This project aims to predict whether a Pathrise fellow will ultimately be placed at a company and estimate the time until placement. Pathrise is a career accelerator that helps individuals land their dream job in tech through mentorship, training, and job search support. By analyzing historical data on Pathrise fellows, we build predictive models to derive insights into placement outcomes and timeframes.

## Dataset
The dataset used in this project contains anonymized data on Pathrise fellows, including various features such as education background, work experience, technical skills, mentor interactions, and job search progress. Additionally, the dataset includes labels indicating whether a fellow was ultimately placed at a company and the time taken for placement.

## Models
### We explore two types of predictive models:

1- Linear Regression: We use linear regression to predict the expected time until placement for Pathrise fellows. By analyzing the relationship between input features and placement duration, we aim to provide insights into how long a fellow can expect to wait before securing a job.

2- Classification Model: In addition to predicting placement duration, we develop a classification model to predict whether a fellow will be placed at a company. By classifying fellows into placed and not-placed categories based on their features, we aim to identify factors that contribute to successful job placement.

## Visualization
Visualization plays a crucial role in understanding model performance and feature importance. We utilize various visualization techniques, including:

### Scatter Plots: 
Visualizing the relationship between input features and placement duration to identify trends and patterns.
### Regression Plot: 
Plotting actual vs. predicted placement duration to evaluate the performance of the linear regression model.
### Confusion Matrix: 
Visualizing the performance of the classification model through a confusion matrix, showing true positive, true negative, false positive, and false negative predictions.
### Feature Importance Plot: 
Analyzing feature importance scores to understand which factors are most influential in predicting placement outcomes.

## Usage
To replicate our analysis and run the predictive models:

1- Clone the Repository: Clone this GitHub repository to your local machine.

2- Install Dependencies: Install the required Python libraries specified in the requirements.txt file.

3- Explore the Notebooks: Explore the Jupyter notebooks in the notebooks directory, which contain the code for data preprocessing, model training, and visualization.

4- Run the Code: Execute the code cells in the notebooks to train the predictive models and generate visualizations.

5- Interpret Results: Analyze the model outputs and visualizations to derive insights into Pathrise fellow placement outcomes and timeframes.

## License
This project is licensed under the MIT License.

## Credits
This project was developed by Mahdi Tahan and Think Group as part of Data Roadmap's data science capstone project.

