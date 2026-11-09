# Iris Classification Model

## Description
This project implements a Machine Learning classification model using the Iris dataset. The objective is to predict the species of an iris flower based on its physical characteristics.

## Technologies Used
- Python 3.11
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Joblib

## Dataset
The Iris dataset contains 150 samples from three different flower species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Each sample contains four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Model
A Random Forest Classifier was trained using the following configuration:
- Number of estimators: 100
- Test size: 20%
- Random state: 42

## Results

Model accuracy: **90%**

The model correctly classified 27 out of 30 test samples.

## Project Structure

```text
proyectoIris/
├── models/
│   └── iris_model.joblib
├── src/
│   └── train.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Execution

1. Clone the repository:

```bash
git clone https://github.com/Reyes-codes/proyectoIris.git
cd proyectoIris
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Train the model:

```bash
python src/train.py
```

## Author
Machine Learning academic project.
