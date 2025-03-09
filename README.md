# Heart Disease Prediction Using Machine Learning

## Overview

This project applies machine learning techniques to predict heart disease based on clinical patient data. The dataset consists of 918 patient records with 12 key features, such as age, blood pressure, cholesterol levels, and exercise-induced angina. The goal is to determine the most effective model for accurate and interpretable predictions.

## Key Features

- **Data Preprocessing:**
  - Handling missing values using K-Nearest Neighbors (KNN) imputation.
  - Standardizing numerical features using Min-Max scaling.
  - One-hot encoding categorical variables.
- **Exploratory Data Analysis (EDA):**
  - Visualizing feature distributions and detecting anomalies.
  - Identifying key predictors through correlation analysis.
- **Machine Learning Models Implemented:**
  - **CART (Decision Trees)**: Accuracy = 80%
  - **C5.0 Decision Trees**: Accuracy = 83%
  - **Random Forest**: Accuracy = 81%
  - **Naïve Bayes**: Accuracy = 81%
  - **Neural Networks**: Accuracy = 87%
- **Model Evaluation:**
  - Performance measured using **accuracy, precision, recall, and F1-score**.
  - Comparison of model interpretability for clinical use.

## Technologies Used

- Python (Pandas, NumPy, Scikit-Learn, TensorFlow, Seaborn, Matplotlib)
- Jupyter Notebook for development and visualization
- GitHub for version control and collaboration

## Results

- The **C5.0 Decision Tree** provided a strong balance of accuracy (83%) and interpretability, making it the most suitable model for clinical use.
- **Neural Networks** achieved the highest accuracy (87%) but lacked transparency, making it less favorable for medical decision-making.
- **Random Forest** was useful for feature importance analysis, highlighting key predictors like ST_Slope and ExerciseAngina.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Final Project Python.ipynb"
   ```

## Future Work

- Exploring ensemble methods for improved performance.
- Enhancing explainability in deep learning models.
- Expanding the dataset to improve generalization.

## Contributors

- **Gerard Corrales**
- **Gabriel Duffy**
