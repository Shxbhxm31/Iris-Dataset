# 🌸 Iris Classifier 🌸

This project develops a machine learning model to classify **Iris flowers** into one of three species using features such as sepal length, sepal width, petal length, and petal width.

## 📂 Dataset

- **Source**: Included `IRIS.csv`
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **Target**: `species` (Iris-setosa, Iris-versicolor, Iris-virginica)

## 🧪 Project Goals

- Classify Iris flowers using a supervised machine learning approach.
- Identify the most significant features contributing to species classification.
- Evaluate the model using metrics like accuracy, confusion matrix, and classification report.

##  Requirements

pandas
numpy
seaborn
matplotlib
scikit-learn
joblib


## ⚙️ Model Pipeline

1. **Data Loading** and **Exploratory Data Analysis (EDA)**
2. **Label Encoding** of the species
3. **Train-Test Split** (80/20)
4. **Model Training** using `RandomForestClassifier`
5. **Evaluation** using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. **Feature Importance Visualization**
7. **Model Export** using `joblib`

## 📈 Results

- **Accuracy**: 100% on test data
- **Top Features**:
  - Petal Length
  - Petal Width

## 🧰 How to Run

```bash
pip install -r requirements.txt
python src/model.py
```

## 📁 Project Structure

```
iris-classifier/
│
├── data/
│   └── IRIS.csv
├── model/
│   ├── random_forest_model.pkl
│   ├── label_encoder.pkl
│   └── feature_importance.png
├── src/
│   └── model.py
├── requirements.txt
└── README.md
```

