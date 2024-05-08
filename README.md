Breast Cancer Classification
This project implements machine learning algorithms to classify breast cancer tumors as malignant or benign based on various features extracted from medical imaging.

----------------------------------------------------------------------Introduction-------------------------------------------------------------------------------------------------------------
Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate diagnosis are crucial for effective treatment. Machine learning techniques offer a promising approach to assist in the diagnosis of breast cancer based on features extracted from medical imaging.

This project explores the use of logistic regression, support vector classifier (SVC), and histogram-based gradient boosting classifier to classify breast cancer tumors using the Breast Cancer Wisconsin (Diagnostic) dataset.

----------------------------------------------------------------------Dataset------------------------------------------------------------------------------------------------------------------
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is available in the sklearn.datasets module. This dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, and the target variable indicates whether the tumor is malignant (0) or benign (1).

----------------------------------------------------------------------Preprocessing------------------------------------------------------------------------------------------------------------
Before training the models, the dataset underwent preprocessing, including:

Scaling of features using StandardScaler.
Splitting the dataset into training and testing sets.
----------------------------------------------------------------------Model Performance--------------------------------------------------------------------------------------------------------
Logistic Regression:
Accuracy on Test data: 96%
Precision:
Malignant (0): 97%
Benign (1): 95%
Recall:
Malignant (0): 91%
Benign (1): 99%
F1-score:
Malignant (0): 94%
Benign (1): 97%
ROC-AUC: 0.99
Histogram-based Gradient Boosting Classifier:
Accuracy on Test data: [accuracy score]
----------------------------------------------------------------------Usage--------------------------------------------------------------------------------------------------------------------
To use this project, follow these steps:
Clone the repository to your local machine.
Install the required dependencies (scikit-learn, pandas, seaborn, matplotlib, numpy, scikit-plot) using pip or conda.
Run the Jupyter notebook Breast_Cancer_Classification.ipynb to train and evaluate the models.


  ----------------------------------------------------------------Clone the repository to your local machine.----------------------------------------------------------------------------------

Install the required dependencies (scikit-learn, pandas, seaborn, matplotlib, numpy, scikit-plot) using pip or conda.
Run the Jupyter notebook Breast_Cancer_Classification.ipynb to train and evaluate the models.
Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or create a pull request.



