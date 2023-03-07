

# Automated Classification of Breast Cancer Tumors Using Machine Learning Techniques.   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anik199/Breast-Cancer-A-Z/blob/main/Breast_cancer2.ipynb)


Breast cancer is a deadly disease that affects millions of women worldwide. Early detection is crucial for better treatment outcomes. The goal of this project is to analyze a dataset of breast cancer patients to predict if the cancer is malignant or benign.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset, which contains measurements of various characteristics of breast cancer cells. The dataset has 569 rows and 32 columns, and is provided as a CSV file. You can find more information about the dataset in the `breast_cancer.csv` file.

## Project Structure

The project is implemented in Python and uses the following libraries:

- Pandas for data manipulation
- Scikit-learn for data preprocessing and modeling
- Matplotlib and Seaborn for data visualization

The project is structured as follows:

- `Breast_cancer2.ipynb`: The Jupyter notebook containing the code for the project
- `breast_cancer.csv`: The dataset used in the project
- `README.md`: This file

## Analysis

The notebook `Breast_cancer2.ipynb` contains the analysis of the dataset. The analysis includes:

- Loading the dataset
- Exploring the dataset
- Data preprocessing
- Modeling
- Evaluation
- Conclusion

The modeling is done using the following algorithms:
- Random Forest
- XGBoost (eXtreme Gradient Boosting)

The evaluation is done using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score

## Conclusion

Based on the analysis, the XGBoost algorithm provided the best performance for predicting if a breast cancer tumor is malignant or benign, with an accuracy of 0.98. 

## How to Use 

To use this project, you can clone the repository and run the `Breast_cancer2.ipynb` notebook using Jupyter or any other compatible notebook application.

```sh
git clone https://github.com/anik199/Breast-Cancer-A-Z.git
cd Breast-Cancer-A-Z
jupyter notebook Breast_cancer2.ipynb
```

## References

- [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
