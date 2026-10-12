# College Admission Prediction — Accuracy Improvement

**Author:** Soumalya Pal  
**Program:** Data Science & Business Analytics / Machine Learning  
**Project type:** Machine Learning

## Overview
A model-comparison project that evaluates a baseline logistic regression workflow against an improved approach for admission prediction.

## Objectives
- Inspect and understand the dataset.
- Prepare data for machine learning.
- Train and compare suitable models.
- Evaluate model performance using appropriate metrics.
- Interpret the results and document limitations.

## Workflow and Key Features
Dataset inspection, EDA, an 80/20 holdout split, categorical encoding for coded variables, stratified 5-fold cross-validation/model selection, baseline-versus-improved comparison, and discussion of limitations.

## Models
Baseline Logistic Regression and an improved Logistic Regression pipeline with categorical encoding, standardization, and regularization tuning

## Evaluation
Accuracy, cross-validation scores, confusion matrix, and ROC-AUC (as reported by the notebook)

> Results should be taken from the executed notebook. No performance figures are claimed in this README unless they are verified from the notebook output.

## Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn (where used)
- Scikit-learn

## Project Files
- `admission_prediction_accuracy_improvement.ipynb` — notebook containing the project workflow.

## Dataset
Expected dataset: The notebook's embedded/loaded admission dataset workflow

**Important:** Review the notebook's dataset-loading cell before running it on another computer. The dataset is not separately included in this package. Make sure you have permission to redistribute any dataset before uploading it to a public repository.

## How to Run
1. Download or clone this repository.
2. Install Python and Jupyter Notebook, or open the notebook in Google Colab.
3. Install the libraries used in the notebook if they are not already available.
4. Add the required dataset in the location expected by the notebook.
5. Open `admission_prediction_accuracy_improvement.ipynb` and run the cells from top to bottom.

Typical packages used in these projects:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Limitations
Model performance depends on the dataset, preprocessing choices, and evaluation split. Predictions are for educational and portfolio purposes and should not be treated as professional financial, property, or admissions advice.

## Author
**Soumalya Pal**
