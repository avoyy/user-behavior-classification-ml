# User Behavior Classification Model | Python, Machine Learning

## Description
Classifies user behavior patterns based on device usage metrics.
Demonstrates data preprocessing, feature selection, model training,
and evaluation using Python and scikit-learn.

## Features
- Data cleaning and preprocessing with pandas
- Exploratory data analysis and visualization with seaborn/matplotlib
- Model training and comparison: Decision Tree, Random Forest, Gradient Boosting, SVM
- Model evaluation: Accuracy, Confusion Matrix, Classification Report
- Optional clustering analysis with KMeans

## Files
- `UserBehaviorModel.ipynb` — Full Jupyter notebook with analysis and model training
- `datasets/user_behavior_dataset.csv` — Input dataset (optional if large; see usage)

## Usage
1. Install required Python packages:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```
2. Open the notebook in Jupyter:
```
jupyter notebook UserBehaviorModel.ipynb
```
3. Ensure the dataset path in the notebook matches the location of your CSV file. Example:
```python
data = pd.read_csv('datasets/user_behavior_dataset.csv')
```
4. Run all cells to perform preprocessing, model training, evaluation, and visualizations.

## Example Output
Accuracy:
```
87%
```
Confusion Matrix:
```
[[45  5]
 [ 7 43]]
```

## Notes
- The notebook demonstrates Python proficiency in data handling, machine learning workflows, and model evaluation.
