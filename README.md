# Fruit Classifiers: End-to-End ML Pipeline & Analysis

This repository contains a comprehensive sequence of Jupyter Notebooks implementing a complete machine learning workflow. The project covers the entire lifecycle—from dataset generation and preprocessing to advanced classification, dimensionality reduction, and clustering.

The project was done with [efemantarci](https://github.com/efemantarci) and   [kerembozkurt](https://github.com/kerembozkurt2002)

---

##  Getting Started

### Environment
* **Google Colab:** These notebooks are designed to run in Google Colab for ease of use and consistent environments.
* **Google Drive:** Ensure you mount your Google Drive at the start of the notebooks to access shared data files and save intermediate outputs (like PCA results).

### How to Run
1.  **Direct Upload:** Upload the project folders to your Google Drive and run the notebooks in the execution order listed below.

##   Project Structure & Execution Order

The project is split into two main phases. **Note:** Phase 1 should be completed before Phase 2.

### Phase 1: Data Engineering & Baseline Modeling
Focuses on building the foundation of the dataset and testing initial logic.

1.  **`DataSetCreation.ipynb`**: Generates the raw dataset used for this project.
2.  **`ProcessData.ipynb`**: Handles the data cleaning and preprocessing pipeline.
3.  **`OneHotCoding.ipynb`**: Converts categorical data into numerical format using One-Hot Encoding for model compatibility.
4.  **`SimilarityCheck.ipynb`**: Performs analysis to check for inter-class and intra-class similarity.
5.  **`LogisticRegression.ipynb`**: Trains and evaluates a baseline Logistic Regression model.

### Phase 2: Advanced Classifiers, PCA & Clustering
Focuses on model optimization, outlier detection, and unsupervised learning.

* **`All_Classifiers.ipynb`**: Runs a comprehensive suite of classifier models on the processed dataset.
* **`SVM.ipynb`**: Implements a soft-margin Support Vector Machine and visualizes support vectors.
* **`SVM_outlier.ipynb`**: Implements our proposed outlier detection framework using SVM logic.
* **`PCA.ipynb`**: **(CRITICAL)** Runs Principal Component Analysis to reduce dimensionality. *This must be run before any PCA-suffixed files.*
* **`Clustering.ipynb`**: Runs K-means++ clustering on the original feature set.
* **`PCA_All_Classifiers.ipynb`**: Executes the classifier suite specifically on the PCA-transformed data.
* **`Clustering_PCA.ipynb`**: Executes K-means++ clustering on the PCA-transformed data.

---

##  Key Features
* **End-to-End Pipeline:** From raw data generation to final model evaluation.
* **Dimensionality Reduction:** Comparison of model performance before and after PCA.
* **Outlier Detection:** A custom framework built on SVM to identify and handle data anomalies.
* **Unsupervised Learning:** Implementation of K-means++ to find natural groupings in the fruit dataset.

**IMPORTANT NOTE** : Link for image dataset (for huggingface) will be provided after the upload is done.

