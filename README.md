<!-- Add a banner image at the top -->
<img src="Purchase_Predict.png" alt="Customer Behavioral Patterns Classification" style="width: 100%;" />

# Customer Behavioral Patterns Classification

## Table of Contents
- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Suggestions for Improvement](#suggestions-for-improvement)

## About the Project
This project involves building a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The analysis includes data preprocessing, model training, evaluation, and providing insights into model performance.

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, sklearn, matplotlib

### Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/yourusername/customer-behavior-classification.git
cd customer-behavior-classification
pip install -r requirements.txt
```

## Dataset
The dataset includes demographic and behavioral data of customers, with instances indicating whether a customer made a purchase or not. It has been preprocessed to handle missing values and encoded categorical variables for compatibility with the machine learning model.

## Usage
Open the Jupyter notebook and follow the steps to preprocess the data, train the model, and evaluate its performance.

```bash
jupyter notebook PRODIGY_DS_03.ipynb
```

## Results
### Confusion Matrix
- **True Negatives:** 6881
- **False Positives:** 470
- **False Negatives:** 422
- **True Positives:** 465

The model performs well in predicting 'no' but struggles with 'yes'.

### Classification Report
- **Precision ('no'):** 0.94
- **Precision ('yes'):** 0.50
- **Recall ('no'):** 0.94
- **Recall ('yes'):** 0.52
- **Overall Accuracy:** 89%

### Accuracy Calculation
- **Accuracy:** 89%

## Suggestions for Improvement
To improve the model, address class imbalance through resampling or class weights, explore additional features, tune hyperparameters, use cross-validation, and consider ensemble methods for better performance.
