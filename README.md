# Music Genre Classification

This repository hosts a data science project focused on classifying music genres from audio features. The project is structured as a series of three Jupyter notebooks, guiding the user from initial data exploration to building a complete machine learning pipeline.

---

## 🚀 Project Overview

The primary objective is to build a robust classifier that can accurately predict the genre of a song based on a set of its technical features. This involves several key stages of a typical machine learning workflow: data cleaning, exploratory data analysis, model selection, and the creation of a reproducible pipeline for deployment.

---

## 📂 Repository Structure

The project is divided into three notebooks, each handling a distinct part of the process.

### 1. `ML - Workshop Final - EDA.ipynb`

This notebook covers the initial **Exploratory Data Analysis (EDA)** and preprocessing of the dataset.

**Key activities include:**
* Loading and inspecting the raw dataset.
* Creating visualizations to understand feature distributions and correlations.
* Identifying and handling missing data and outliers.
* Saving the cleaned dataset for the next stage.

### 2. `ML - Workshop Final - Models.ipynb`

Using the cleaned data, this notebook focuses on training and evaluating several machine learning models to find the best performer for our classification task.

**Models Compared:**
* Logistic Regression
* Decision Tree
* Support Vector Classifier (SVC)
* Random Forest
* XGBoost

Performance is measured using standard classification metrics like accuracy, precision, recall, and F1-score to ensure a fair comparison.

### 3. `ML - Workshop Final - Pipeline.ipynb`

The final notebook consolidates the entire workflow into a single, reusable **Scikit-learn Pipeline**. This makes the model easy to deploy and use for predictions on new data.

**Pipeline Steps:**
1.  **Cleaning:** Automates the data cleaning steps identified during EDA.
2.  **Transformation:** Applies feature scaling to prepare the data for the model.
3.  **Training:** Fits the best-performing model from the previous notebook.
4.  **Deployment:** The final pipeline is serialized, making it ready for integration into a production environment.

---

## 😎  Try it! 

[Demo Link](https://huggingface.co/spaces/jggomez/Genre-classification)

![Screenshot 2025-06-10 at 10 56 10 p m](https://github.com/user-attachments/assets/5aaed0e1-0b6b-407d-a9c9-eba30f3efd22)


## 🛠️ Getting Started

To get this project running on your local machine, follow these steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Install dependencies:**
    It is highly recommended to use a virtual environment to manage dependencies.
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file with libraries such as pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, and jupyter.)*

3.  **Launch Jupyter:**
    Open the notebooks and run them in order, starting with the EDA notebook.
    ```bash
    jupyter notebook
    ```

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
