# Project Title

Mental Health Data Analysis Project

## Project Description

This project analyzes a mental health dataset using Python and object-oriented programming (OOP) principles. It covers data collection, understanding, preprocessing, analysis, model training, and model storage.

## Project Structure

- `OOP/`: Directory for this OOP-related resources.
- `Project.ipynb`: Main Jupyter notebook containing all code and analysis.
- `mental_health_dataset.csv`: The dataset used for analysis.

## Main Steps

1. **Libraries**: Import necessary libraries such as pandas, numpy, seaborn, matplotlib, and scikit-learn.
2. **Data Collection**: Load and display the dataset using the `Datacollector` class.
3. **Data Understanding**: Explore the dataset structure and contents with the `DataUnderstanding` class.
4. **Data Preprocessing**: Clean and prepare the data using the `DataPreprocessing` class.
5. **Univariate & Bivariate Analysis**: Analyze individual features and relationships between features.
6. **Data Splitting**: Split the data into training and testing sets using the `DataSplitter` class.
7. **Model Training**: Train a Support Vector Machine (SVM) regression model with the `ModelTrainer` class.
8. **Model Storage**: Save and load the trained model using the `ModelStorage` class.

## How to Run

1. Open `Project.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell in order to perform data analysis and modeling.
3. The trained model will be saved as `svm_laptop_model.pkl`.

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- pickle

Install dependencies with:
pip install pandas numpy seaborn matplotlib scikit-learn

## Dataset

The dataset file should be named `mental_health_dataset.csv` and placed in the project directory.

---
