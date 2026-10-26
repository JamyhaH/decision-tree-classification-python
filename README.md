# Decision Tree Classification Using Python

## Project Overview

This project implements and evaluates Decision Tree classifiers for a three-class classification problem using Python and Scikit-learn. It demonstrates data preparation, supervised learning, model evaluation, and visualization.

## Dataset

- 541 observations
- 27 numerical input features
- 3 target classes: 0, 1, and 2
- 80% training and 20% testing split, stratified by class

## Technologies Used

Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Google Colab.

## Methodology

1. Loaded and explored the dataset with Pandas.
2. Separated the 27 input features from the target labels.
3. Created an 80/20 stratified training and testing split using `random_state=42`.
4. Trained Decision Tree classifiers with `max_depth=50` and `max_depth=100`.
5. Evaluated accuracy, class-wise sensitivity, specificity, and the confusion matrix.
6. Visualized classification performance using Matplotlib.

## Model Performance

**Test accuracy: 94.50% (103/109 correct predictions)**

| Class | Sensitivity | Specificity |
|---|---:|---:|
| Class 0 | 92.31% | 98.80% |
| Class 1 | 96.00% | 95.24% |
| Class 2 | 94.83% | 98.04% |

Both configurations produced the same predictions. The trained tree reached an actual depth of 8, below both maximum-depth settings.

## Confusion Matrix

| Actual / Predicted | Class 0 | Class 1 | Class 2 |
|---|---:|---:|---:|
| Class 0 | 24 | 2 | 0 |
| Class 1 | 0 | 24 | 1 |
| Class 2 | 1 | 2 | 55 |

[View the Python notebook and confusion matrix visualization](BE604_Project2.ipynb)

## How to Run

1. Open `BE604_Project2.ipynb` in Google Colab.
2. Install any missing Python dependencies: `pandas`, `numpy`, `scikit-learn`, and `matplotlib`.
3. Obtain the GCL dataset from an authorized source and upload it when prompted.
4. Run the notebook cells in order.

## Skills Demonstrated

- Supervised machine learning and multiclass classification
- Data preparation and train/test splitting
- Model training with Scikit-learn
- Evaluation using accuracy, sensitivity, specificity, and confusion matrices
- Data visualization with Matplotlib

## Future Improvements

- Compare performance with Random Forest and other classifiers.
- Use cross-validation for more robust performance estimates.
- Explore hyperparameter tuning and feature importance.

## Project Notes

This project was developed as part of my hands-on learning in Python and machine learning. The reported results come from one stratified train/test split and should not be interpreted as guaranteed performance on new datasets.
