# Decision Tree Classification Using Python

## Project Overview
This project demonstrates the implementation and evaluation of Decision Tree classifiers using Python and Scikit-learn. The objective was to classify observations into three categories and evaluate model performance using accuracy, sensitivity, specificity, and a confusion matrix.

## Dataset
- 541 observations
- 27 predictive features
- 3 classification categories (0, 1, and 2)
- 80% training and 20% testing split

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Methodology
1. Imported and explored the dataset using Pandas.
2. Separated the 27 predictive features from the class labels.
3. Split the dataset into training and testing subsets using stratified sampling.
4. Trained Decision Tree classifiers with maximum depths of 50 and 100.
5. Evaluated model performance using accuracy, sensitivity, specificity, and a confusion matrix.
6. Visualized the classification results using Matplotlib.

## Results

**Overall Classification Accuracy: 94.50%**

| Class | Sensitivity | Specificity |
|---|---|---|
| Class 0 | 92.31% | 98.80% |
| Class 1 | 96.00% | 95.24% |
| Class 2 | 94.83% | 98.04% |

Both classifiers achieved the same performance, with an actual tree depth of 8.

## Confusion Matrix


The model correctly classified 103 out of 109 testing observations.

## Key Takeaways
This project strengthened my understanding of supervised machine learning, classification algorithms, model evaluation, and Python-based data analysis. It also provided practical experience with Scikit-learn and interpreting multiclass classification results.

## Future Improvements
- Compare Decision Trees with Random Forest classifiers.
- Explore cross-validation and hyperparameter tuning.
- Evaluate model performance on additional datasets.
- Investigate feature importance and model interpretability.

## How to Run
1. Download the Jupyter notebook (`BE604_Project2.ipynb`).
2. Install the required libraries listed in `requirements.txt`.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Provide the GCL dataset from an authorized source.
5. Run the notebook cells sequentially.
