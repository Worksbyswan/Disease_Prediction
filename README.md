# Disease_Prediction
# 🧬 Disease Prediction Using Machine Learning

An interactive machine learning application that demonstrates breast cancer classification using Logistic Regression and Random Forest. Built with Python, Scikit-learn, and Streamlit, the application compares classification models and presents their evaluation metrics through an interactive dashboard.

**CodeAlpha Machine Learning Internship — Task 4: Disease Prediction from Medical Data**

## 🚀 Features

* Breast cancer classification using machine learning.
* Logistic Regression model.
* Random Forest classifier.
* Comparison of model performance.
* Accuracy, precision, recall, F1-score, and ROC-AUC metrics.
* Confusion matrix visualization.
* ROC curve visualization.
* Classification report.
* Random Forest feature importance visualization.
* Interactive prediction interface.
* Dataset statistics and feature summaries.

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Streamlit

## 📊 Dataset

This project uses the **Breast Cancer Wisconsin Diagnostic Dataset**, available through Scikit-learn.

Dataset details:

* Total samples: 569
* Number of numerical features: 30
* Classification categories: Benign and malignant

The features are derived from digitized images of fine-needle aspirates of breast masses.

The dataset is loaded directly through Scikit-learn, so a separate CSV download is not required.

## 🧠 Machine Learning Models

### 1. Logistic Regression

A supervised classification algorithm used to predict the target class. Feature scaling is performed using StandardScaler within a machine learning pipeline.

### 2. Random Forest

An ensemble learning algorithm that combines multiple decision trees to perform classification.

The application compares both models using a held-out test dataset.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/CodeAlpha_DiseasePrediction.git
cd CodeAlpha_DiseasePrediction
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

**Linux/macOS:**

```bash
source .venv/bin/activate
```

### 4. Install dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Run the application

```bash
python -m streamlit run app.py
```

Open the local URL displayed in the terminal to access the dashboard.

## 📈 Model Evaluation

The application evaluates both classifiers using:

| Metric    | Purpose                                                           |
| --------- | ----------------------------------------------------------------- |
| Accuracy  | Measures the overall proportion of correct predictions.           |
| Precision | Measures the proportion of positive predictions that are correct. |
| Recall    | Measures the proportion of actual positive cases identified.      |
| F1-score  | Combines precision and recall into a single metric.               |
| ROC-AUC   | Evaluates the model's ability to distinguish between classes.     |

The application also provides a confusion matrix, ROC curve, classification report, and model comparison chart.

Metrics are calculated when the application runs rather than being hard-coded.

## 📁 Project Structure

```text
CodeAlpha_DiseasePrediction/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🔮 Future Improvements

* Hyperparameter tuning.
* Cross-validation.
* Additional model comparisons.
* Improved feature explainability.
* Model persistence and versioning.
* Evaluation on additional appropriately licensed datasets.

## ⚠️ Medical Disclaimer

This project is intended exclusively for educational and demonstration purposes. It is not clinically validated and must not be used for medical diagnosis, screening, treatment decisions, or patient care.

Model predictions are not medical advice and should not be interpreted as an individual's actual disease risk.
