# Breast Cancer Classifier Using K-Nearest Neighbors

## Project Overview
This project aims to develop a machine learning model that can classify whether a tumor is benign or malignant based on features extracted from breast cancer cell nuclei. The dataset used for this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the `sklearn.datasets` library. The classification is achieved using the **K-Nearest Neighbors (KNN)** algorithm.

## Dataset
The **Breast Cancer Wisconsin (Diagnostic) Dataset** contains the following information:
- **Number of Instances**: 569
- **Number of Features**: 30 (plus a target variable)
- **Feature Information**: 
  - Mean radius
  - Mean texture
  - Mean perimeter
  - Mean area
  - Mean smoothness
  - And others related to the cell nuclei's properties
- **Target Variable**: 
  - 0: Malignant
  - 1: Benign

## Project Steps
1. **Load Dataset**: The dataset is loaded using `sklearn.datasets.load_breast_cancer()`.
2. **Data Preprocessing**: The dataset is split into training and test sets using `train_test_split`.
3. **Model Building**: A K-Nearest Neighbors (KNN) model is built using the `KNeighborsClassifier` from `sklearn.neighbors`.
4. **Model Evaluation**: The model's performance is evaluated using accuracy scores and visualized using matplotlib plots.

## Installation and Requirements
To run this project, you'll need to install the following Python packages:
- `scikit-learn`
- `matplotlib`
- `pandas` (optional for additional data handling)

You can install them using `pip`:
```bash
pip install scikit-learn matplotlib pandas
```

## Running the Project
1. Clone the repository or download the notebook file.
2. Ensure the necessary libraries are installed.
3. Open the notebook file (`Breast_Cancer_Classifier.ipynb`) and run the cells step by step.

## Conclusion
This project demonstrates a simple yet effective approach to classifying breast cancer using the K-Nearest Neighbors algorithm. The model provides insights into how machine learning techniques can aid in medical diagnosis tasks.