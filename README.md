# Credit Score Class Classification
> Submitted for DSN2099 - Project Exhibition II (University Course Project)

## Description
This project builds a machine learning model to classify individuals’ credit scores into categories such as Poor, Standard, and Good, based on financial and personal data.
- Data preprocessing and feature engineering
- Model training with Logistic Regression, SVM, Random Forest, and ensemble methods
- Evaluation using accuracy, precision, recall, and F1-score metrics
- Visualization of feature importance and correlation

## Features
- Preprocessing of categorical and numerical data
- Handling of ordinal and non-ordinal variables
- Stratified data splitting for balanced training and testing
- Hyperparameter tuning with Grid Search
- Ensemble learning (Voting and Stacking Classifiers)

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / IPython

## Project Structure
```
credit-score-classification/
├── credit_score_classification.ipynb # Jupyter Notebook with full EDA and modeling
├── credit_score_data.csv # Dataset CSV file
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

## Installation & Usage
1. **Clone this repository:**
```
git clone https://github.com/mahesh-kakde/credit-score-classification.git
cd credit-score-classification
```
2. **Install dependencies:**
```
pip install -r requirements.txt
```
3. **Run the Jupyter Notebook:**
```
jupyter notebook credit_score_classification.ipynb
```

Follow the notebook to explore the data, train models, tune hyperparameters, and evaluate results.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Author
Mahesh Kakde  
[LinkedIn](https://linkedin.com/in/mahesh-kakde)  
[GitHub](https://github.com/mahesh-kakde)
