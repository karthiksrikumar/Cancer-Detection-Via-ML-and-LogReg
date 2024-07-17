Cell Classification using Logistic Regression
This project uses machine learning techniques, specifically logistic regression, to classify cell biopsies as either malignant or benign based on various cellular features.
Dataset
The dataset contains the following features:

diagnosis: Whether the tumor was diagnosed as malignant (1) or benign (0).
perimeter_mean: The average perimeter of cells in the biopsy
radius_mean: The average radius of cells in the biopsy
texture_mean: The average texture of cells in the biopsy
area_mean: The average area of cells in the biopsy
smoothness_mean: The average smoothness of cells in the biopsy
concavity_mean: The average concavity of cells in the biopsy
symmetry_mean: The average symmetry of cells in the biopsy

Note: The term "mean" refers to the average value for each feature across all cells in a given biopsy.
Project Structure
This project is implemented in a Jupyter Notebook (.ipynb) file, which contains the following main sections:

Data Loading and Preprocessing
Exploratory Data Analysis
Logistic Regression with Multiple Features
Model Creation and Training
Visualization and Interpretation
Model Predictions
Model Performance Evaluation

Logistic Regression
Logistic regression is used for binary classification, providing "soft" predictions in the form of probabilities. The model combines multiple features to improve classification accuracy.
Confusion Matrices
The project includes the creation and visualization of confusion matrices to evaluate model performance.
Requirements

Python 3.x
Jupyter Notebook
Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Usage

Open the Jupyter Notebook file.
Run the cells in order to reproduce the analysis and results.
Modify parameters or add new features as needed for further experimentation.
