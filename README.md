# 🩺 Diabetes Prediction using K-Nearest Neighbors (KNN) and Exploratory Data Analysis (EDA)

This project performs **exploratory data analysis (EDA)** and builds a **K-Nearest Neighbors (KNN)** model to predict diabetes based on health-related features. The dataset used is the popular **PIMA Indian Diabetes Dataset**.

---

## 📂 Project Structure

diabetes-predictor/
├── data/diabetes.csv # PIMA Indian Diabetes Dataset 
├── EDA_Diabetes.ipynb # Data exploration and visualization
├── DiabetesKNN.ipynb # KNN model building and evaluation
├── DiabetesKNNClassifier.ipynb # KNN model building and evaluation (own classifier)
├── requirements.txt # List of Python dependencies
├── README.md # Project documentation
└── .gitignore # Ignored files (e.g., venv/, checkpoints)

---

## 📊 Dataset

- **Source**: PIMA Indian Diabetes Dataset
- **Features**: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
- **Target**: Binary outcome — `0` (No Diabetes) or `1` (Diabetes)

---

## 🔍 Exploratory Data Analysis (EDA)

- Handling missing/zero values
- Feature distributions
- Correlation heatmap
- Pairplots and boxplots
- Outlier detection

---

## 🤖 Model: K-Nearest Neighbors (KNN)

- Data normalization using `StandardScaler`
- Train-test split (80/20)
- Model training using `KNeighborsClassifier`
- Model evaluation:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion matrix

---

## 📈 Results

- Achieved accuracy: **~73.37%**
- K value chosen: **K = 5**
- Visualization: Confusion matrix, prediction metrics

---

## Install dependencies using:

```bash
pip install -r requirements.txt
```

## 🚀 Run the Project

Clone the repository:

```bash
git clone https://github.com/guptaksht10/diabetes-predictor.git
cd diabetes-predictor
```

## Create and activate a virtual environment:

```bash
python -m venv venv
# Activate:
# Windows: venv\Scripts\activate
# macOS/Linux: source venv/bin/activate
```

## Install dependencies:

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook:

```bash
jupyter notebook
```

## 📄 License
This project is open-source and available under the MIT License.

