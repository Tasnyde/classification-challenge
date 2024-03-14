# Spam Detection Model Project

## Project Overview
This project aims to develop a machine learning model to accurately detect spam emails for an Internet Service Provider (ISP). Two models, Logistic Regression and Random Forest, are evaluated on their performance in classifying emails into spam and not spam categories.

## Dataset
The dataset used for this project contains features extracted from emails, with labels indicating whether an email is spam (1) or not spam (0). It can be accessed [here](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv).

## Methodology
The project follows these steps:

1. **Data Preprocessing**
   - Splitting the dataset into features (X) and labels (y).
   - Dividing the dataset into training and testing sets.
   - Scaling the features to standardize the data for better model performance.

2. **Model Development**
   - **Logistic Regression Model**: A logistic regression model is implemented and fitted to the scaled training data.
   - **Random Forest Model**: A random forest classifier is implemented and fitted to the scaled training data.

3. **Model Evaluation**
   - Both models are evaluated based on their accuracy scores on the testing set.

## Predictions
Before implementing the models, a prediction was made regarding which model would perform better. Given the complexity of patterns in spam detection, the random forest model was hypothesized to outperform the logistic regression model.

## Results
- The accuracy of each model is reported.
- A comparison is made between the predicted and actual model performances.

## How to Run the Project
1. **Clone the Repository**: Clone this project to your local machine.
2. **Install Requirements**: Ensure Python and necessary libraries (pandas, sklearn, etc.) are installed.
3. **Execute the Notebook**: Run the `spam_detector.ipynb` notebook to reproduce the analysis and models.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook or JupyterLab

### Prerequisites

The starter files consist of the following files:  
- `spam_detector.ipynb`

## Contributing
This project benefits from the contributions of:
- edX Boot Camps LLC - Educational partner providing guidance and resources.

## Authors
* **edX Boot Camps** - *Initial work* 
* **Todd Snyder** - *Final work*

## Acknowledgements
We thank the providers of the dataset and acknowledge the use of open-source software in this project.
