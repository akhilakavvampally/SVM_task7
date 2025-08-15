# SVM_task7
Usinng SVM for linear and non-linear classification
This project demonstrates Support Vector Machines (SVM) for binary classification using the Breast Cancer Dataset.
It covers:

Linear and RBF kernel SVM models.

PCA-based visualization of decision boundaries in 2D space.

Hyperparameter tuning using GridSearchCV.

Cross-validation for performance evaluation.

The code is built to run in Google Colab and follows the requirements from Task 7 of the AI & ML Internship program
.

📂 Dataset

Source: Breast Cancer Dataset (Scikit-learn)

Target: Binary classification (Malignant vs. Benign tumors).

Features: 30 numerical features about cell nuclei.

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/svm-task7.git
cd svm-task7

2️⃣ Open in Google Colab

Upload the svmwithPCAtask7.ipynb file to Google Colab

Or, open directly from GitHub using:

# In Colab
from google.colab import drive
drive.mount('/content/drive')

📜 Code Structure

Data Loading: Loads Breast Cancer dataset.

Preprocessing: Standardizes features using StandardScaler.

Dimensionality Reduction: Applies PCA (2 components) for visualization.

Model Training:

Linear SVM (kernel='linear')

RBF SVM (kernel='rbf')

Hyperparameter Tuning: Uses GridSearchCV to optimize C and gamma.

Evaluation: Classification report, confusion matrix, and cross-validation accuracy.

📊 Results

Linear SVM: Works well if data is nearly linearly separable.

RBF SVM: Handles complex, non-linear boundaries.

Best Params (Example): C=10, gamma=0.01 (may vary).

Accuracy: ~97–99% after tuning.

🖼 Visualization

Decision boundaries are shown in PCA space (2D projection).

Helps understand how the SVM is separating classes.

🚀 How to Run

Open the .ipynb in Colab.

Run all cells sequentially.

Adjust parameters in the code (e.g., C, gamma) to explore model behavior.

