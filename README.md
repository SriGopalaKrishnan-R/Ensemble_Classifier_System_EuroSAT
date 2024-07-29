# Enhancing Satellite Imagery Analysis through Modeling and Optimization of Hybrid Classifier System
Creating a multiple classifier system to enhance the satellite imagery analysis and its performance metrics.
Here the data is uploaded as sample population since the dataset is huge ,for understanding purpose of various classes.

# Overview
This project focuses on enhancing the analysis of satellite imagery by developing and optimizing a hybrid classifier system. The system integrates multiple machine learning models, including K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest (RF), and XGBoost, to achieve superior performance in land use and land cover classification.

# Achievements
*) Accuracy: 97% after fine-tuning with grid search.
*) Models Used: KNN, SVM, RF, XGBoost.
*) Optimization Libraries: Hyperopt, Optuna.
*) Evaluation Metrics: Overall Accuracy, Precision, Recall,F1-score.

# Dataset
The dataset used is the EuroSAT dataset, which consists of satellite images of different land use and land cover categories. The dataset is publicly available and widely used for benchmarking land classification tasks.

# Installation
1) Clone the repository: git clone https://github.com/SriGopalaKrishnan-R/Ensemble_Classifier_System_EuroSAT/edit/main/
                         cd Ensemble_Classifier_System_EuroSAT
2) Create and activate a virtual environment: python3 -m venv env
                                              source env/bin/activate  # On Windows use `env\Scripts\activate`
3) Install the required packages: pip install -r requirements.txt

# Usage 
*)Data Preparation
  a)Download the EuroSAT dataset from this link and place it in the data directory.
  b)Preprocess the data by running the appropriate preprocessing script.
*) Then follow the stages of Training,Evaluation.

# Libraries Used
  *) TensorFlow
  *) Keras
  *) PyTorch
  *) NumPy
  *) Scikit-learn
  *) Pandas
  *) OpenCV
  *) Matplotlib
  *) Seaborn
  *) Albumentations
  *) Rasterio
  
# Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
