<img width="203" alt="image" src="https://github.com/user-attachments/assets/dfd81c29-1dd1-4778-9e47-01a5c4a7b034">




### Major Project - IBM Machine Learning Professional Certificate

### Project Title: Printed Circuit Board Defect Detection
### Overview
This repository contains the code, data, and documentation for the Major Project as part of the IBM Machine Learning Professional Certificate. The project aims to implement a machine learning model to predict defects in printed circuit boards (PCB) by using various data preprocessing and modeling techniques.

### Project Objectives
Detect defects in printed circuit boards based on sensor and image data.
Apply machine learning algorithms to classify defects and optimize model accuracy.
Evaluate the performance of models using key metrics such as accuracy, precision, recall, and F1 score.

### Directory Structure

MajorProject-IBM-Machine-Learning/
│
├── data/                  # Dataset used for training and testing
│   └── pcb_data.csv        # Example dataset (replace with your data)
│
├── notebooks/              # Jupyter notebooks for analysis and modeling
│   └── preprocessing.ipynb # Data cleaning and preprocessing
│   └── modeling.ipynb      # Model training and evaluation
│
├── models/                 # Trained model files (optional)
│   └── knn_model.pkl       # Example model (replace with actual model)
│
├── images/                 # Any images or plots generated
│   └── confusion_matrix.png
│
├── README.md               # Project documentation (this file)
└── LICENSE                 # License for the project

### Machine Learning Algorithms Used
K-Nearest Neighbors (KNN): For defect classification based on nearest data points.
Support Vector Machine (SVM): For classification using hyperplanes.
Random Forest: An ensemble method for improving classification performance.

### Evaluation Metrics
Accuracy: Overall accuracy of the model.
Confusion Matrix: A matrix showing the classification performance for each class.
Precision, Recall, and F1 Score: Metrics to evaluate the model's performance in defect detection.

### Results
The KNN model achieved an accuracy of 92% with an F1 score of 0.89.
SVM performed similarly but required more computation time.

### Installation
Clone the repository:
git clone https://github.com/SRNTHMZMD/MajorProject-IBM-Machine-Learning-Professional-Certificate.git

### How to Run

### Data Preprocessing:

Open notebooks/preprocessing.ipynb and run the cells to clean and preprocess the dataset.

### Model Training:

Open notebooks/modeling.ipynb and run the cells to train the model using the provided dataset.

### View Results:

Results such as confusion matrix and accuracy plots are stored in the images/ folder.


### Conclusion
This project successfully implemented machine learning techniques to detect defects in PCBs with high accuracy. Future improvements can include experimenting with deep learning models and using larger datasets.

### License
This project is licensed under the MIT License. See the LICENSE file for more information.

### Acknowledgments
IBM for providing course materials and certification.
Coursera for hosting the IBM Machine Learning Professional Certificate.

### Disclaimer
The solutions offered are intended for reference only and should not be copied directly. If you follow the instructions cautiously, you can complete the programming assignments. Before verifying the answers, try the quizzes on your own. These machine learning classes are basic, with good material and organization.
