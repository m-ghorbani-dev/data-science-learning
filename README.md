# Data Science Learning

A hands-on learning repository covering data analysis, data visualization,
data preprocessing, and machine learning with Python.

This project contains Jupyter notebooks with practical examples designed
to build a solid foundation in Data Science and Machine Learning.

## 🎯 Project Objectives

- Learn Data Science concepts through practical exercises.
- Explore, clean, and preprocess real-world datasets.
- Perform Exploratory Data Analysis (EDA).
- Understand and implement fundamental machine learning algorithms.
- Evaluate and compare machine learning models.
- Practice data collection and web scraping.
- Build a structured portfolio of Data Science projects.

## 📚 Learning Roadmap

### 1. Data Analysis and Preprocessing

| Notebook | Topic |
|---|---|
| [01 - SpaceX Data Exploration](notebooks/01_spacex_data_exploration.ipynb) | Exploratory Data Analysis |
| [02 - Data Cleaning and Preprocessing](notebooks/02_spacex_data_cleaning_preprocessing.ipynb) | Missing Values, Data Cleaning, and Preprocessing |
| [03 - Feature Engineering](notebooks/03_feature_engineering.ipynb) | Feature Preparation and Transformation |

### 2. Classification Algorithms

| Notebook | Topic |
|---|---|
| [04 - Logistic Regression](notebooks/04_logistic_regression.ipynb) | Logistic Regression |
| [05 - K-Nearest Neighbors](notebooks/05_knn_classification.ipynb) | KNN Classification |
| [06 - Decision Tree](notebooks/06_decision_tree_classification.ipynb) | Decision Tree Classification |
| [07 - Random Forest](notebooks/07_random_forest_classification.ipynb) | Ensemble Learning |
| [08 - Support Vector Machine](notebooks/08_support_vector_machine.ipynb) | SVM Classification |
| [09 - Classification Model Comparison](notebooks/09_classification_model_comparison.ipynb) | Model Evaluation and Comparison |

### 3. Regression and Clustering

| Notebook | Topic |
|---|---|
| [10 - Linear Regression](notebooks/10_linear_regression.ipynb) | Regression |
| [11 - K-Means Clustering](notebooks/11_kmeans_clustering.ipynb) | Unsupervised Learning |

### 4. Data Collection

| Notebook | Topic |
|---|---|
| [12 - SpaceX Data Collection](notebooks/12_spacex_data_collection.ipynb) | Dataset Collection and Inspection |
| [13 - Web Scraping Basics](notebooks/13_web_scraping_basics.ipynb) | Extracting Data from Websites |

## 🛠️ Technologies

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Scikit-learn** — Machine learning
- **JupyterLab** — Interactive notebooks

## 📁 Project Structure

```text
data-science-learning/
├── data/
│   ├── raw/
│   │   └── dataset_falcon9.csv
│   └── processed/
│       └── dataset_falcon9_cleaned.csv
├── notebooks/
│   ├── 01_spacex_data_exploration.ipynb
│   ├── 02_spacex_data_cleaning_preprocessing.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_logistic_regression.ipynb
│   ├── 05_knn_classification.ipynb
│   ├── 06_decision_tree_classification.ipynb
│   ├── 07_random_forest_classification.ipynb
│   ├── 08_support_vector_machine.ipynb
│   ├── 09_classification_model_comparison.ipynb
│   ├── 10_linear_regression.ipynb
│   ├── 11_kmeans_clustering.ipynb
│   ├── 12_spacex_data_collection.ipynb
│   └── 13_web_scraping_basics.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/m-ghorbani-dev/data-science-learning.git
cd data-science-learning
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Launch JupyterLab

```bash
cd notebooks
jupyter lab
```

Open the notebook you want to study and run its cells.

> **Note:** Some notebooks require the Falcon 9 dataset in the `data/raw/`
> directory. Check each notebook's dataset path before running it.

## 📊 Dataset

The project includes the following datasets:

- `dataset_falcon9.csv` — Raw Falcon 9 launch data.
- `dataset_falcon9_cleaned.csv` — Processed Falcon 9 launch data.

Check the dataset's original source, license, and redistribution permissions
before sharing it publicly.

## 📈 Learning Approach

The notebooks are organized to support progressive learning through:

1. Understanding the problem and dataset.
2. Exploring and preparing the data.
3. Implementing analytical or machine learning techniques.
4. Visualizing results and evaluating model performance.
5. Interpreting results and identifying limitations.

## 🚀 Future Improvements

- Add more machine learning algorithms.
- Explore feature selection and hyperparameter tuning.
- Add cross-validation and model evaluation techniques.
- Develop end-to-end Data Science projects.
- Improve documentation and reproducibility.

---

**Learning Data Science through practical implementation.**
