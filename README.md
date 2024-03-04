# Income Classification Project
This project is focused on using logistic regression, applying learnings from a machine learning course. It aims to develop a predictive model using a [Census Income](https://archive.ics.uci.edu/dataset/20/census+income) dataset from a 1994 census. The model predicts likelihood of a individuals earning over $50k annually. Our approach involves preprocessing data, training the model with the datasets, and evaluating its performance using distinct metrics.
The process involves training the model with a specific dataset and evaluating its performance on a separate test set.

## Features
- Data Preprocessing: Applies one-hot encoding to categorical features and examines feature correlations to reduce interdependence.
- Model Training: Utilizes training and testing datasets to develop the model and assess its performance.
- Performance Evaluation: Employs distinct metrics to evaluate the model effectiveness, such as Confusion Matrix, Accuracy, Recall, and F1 score.
- Model Insights: Analyzes the model's coefficients to understand their impact on predictions.
- Threshold Analysis: Utilizes the Receiver Operating Characteristic (ROC) curve and calculate the Area Under the Curve (AUC) score to explore differents thresholds and the model's class separation capabilities.

## Setup and installation
You can see the Jupyter Notebook [here](Income%20Classification.ipynb) or can install it locally using the next steps:

**Prerequisite**: This project requires Jupyter Notebook to be installed. If you do not have Jupyter Notebook installed, you can find installation instructions at the [documentation](https://jupyter.org).

To set up and show the notebook locally, follow these steps:
1. Run the following command in your terminal to clone the project repository:
```shell
git clone https://github.com/Joel-Milla/IncomeClassification.git
```
2. Navigate to the cloned project directory and launch Jupyter Notebook to access the .ipynb files.
3. Run cells sequentially using `Shift + Enter`.
