<!-- PROJECT BANNER -->
<p align="center">
  <img src="https://img.shields.io/badge/Data%20Mining%20CW2-Activity%20Recognition-blue?style=for-the-badge" />
</p>

<h1 align="center">📊 Data Mining  
Human Activity Recognition (HAR) Using Smartphone & Smartwatch Data</h1>

<p align="center">
  <strong>MSc Data Science & Artificial Intelligence</strong><br>
  <strong>Author:</strong> Chibuike Lawrence Orji-Oko  
</p>

---

## 📘 Overview

This repository contains my **Data Mining Coursework 2** project, where I built machine learning models to recognise human physical activities using motion sensor data from smartphones and smartwatches.

The dataset used is the **WISDM Smartphone & Smartwatch Activity and Biometrics Dataset**, a large real-world dataset containing accelerometer and gyroscope readings captured during different activities.

The goal of this coursework:

- Perform data preprocessing and exploratory analysis  
- Train multiple classification models  
- Evaluate performance using accuracy, precision, recall, and F1-score  
- Compare results and interpret misclassifications  
- Produce a full academic report summarising findings  

---

## 📂 Repository Structure

```text
data_mining/
│
├── notebooks/
│   └── wisdm_data_mining.ipynb         # Full data analysis & modelling workflow
│
├── reports/
│   └── wisdm_data_mining_report.pdf     # Cleaned public-safe coursework report
│
├── src/
│   └── (Optional Python modules if extended later)
│
├── requirements.txt                  # Python dependencies
└── .gitignore                        # Ignore rules for Python & Jupyter
```
---

## 📦 Dataset

This project uses the WISDM Smartphone & Smartwatch Activity Dataset:

### 📄 Dataset details:
https://archive.ics.uci.edu/dataset/507/wisdm+smartphone+and+smartwatch+activity+and+biometrics+dataset

Because the dataset is very large, it is not included in the repository.

> Note: The notebook assumes the WISDM dataset has been downloaded locally and some cells use 
> local file paths. To run it yourself, update the paths in the notebook to match where you
> stored the dataset on your own machine.


---

## ⚙️ Running the Project

### 1️⃣ Create & activate a virtual environment
python -m venv venv

#### Windows:

venv\Scripts\activate

#### Mac/Linux:

source venv/bin/activate

### 2️⃣ Install dependencies
pip install -r requirements.txt

### 3️⃣ Open the notebook
jupyter notebook

Run all cells to reproduce:

- Data preprocessing

- Visualisations

- Model training

- Model evaluation

---

## 📊 Summary of Results

The notebook demonstrates:

- Feature extraction from raw sensor time-series data

- Training multiple classifiers

- Performance comparison

- Identification of activities with highest/lowest predictive accuracy

**More detailed results and analysis can be found in the full report.**

## 📄 Read the full report:
**👉 reports/wisdm_data_mining_report.pdf**

---

## 📫 Contact

If you'd like to discuss the project or collaborate:

**📧 orjichibyk@gmail.com**

**🔗 GitHub: https://github.com/chibykelaw**
