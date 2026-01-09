# 🔍 Anomaly Detection using DBSCAN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

<div align="center">
  <h3> Detect outliers in high-dimensional data using Density-Based Spatial Clustering of Applications with Noise.</h3>
</div>

---

## 📖 Overview

This project implements **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to identify anomalies (outliers) in a dataset. Unlike K-Means, DBSCAN does not require specifying the number of clusters beforehand and is exceptionally good at finding outliers in non-linearly separable data.

**Key capabilities:**
* **Unsupervised Learning:** Detects anomalies without labeled training data.
* **Noise Handling:** Robustly separates "noise" points (anomalies) from dense clusters.
* **Visualization:** Includes plotting scripts to visualize clusters vs. outliers.

---

## ⚙️ How DBSCAN Works

DBSCAN clusters points based on two key hyperparameters:
1.  **Epsilon ($\epsilon$):** The maximum distance between two samples for one to be considered as in the neighborhood of the other.
2.  **MinPoints:** The number of samples (or total weight) in a neighborhood for a point to be considered as a core point.

> **Anomaly Definition:** Any point that is not a core point and not reachable from a core point is considered an outlier (Noise).

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**
    * `scikit-learn` (DBSCAN implementation)
    * `pandas` (Data manipulation)
    * `numpy` (Numerical operations)
    * `matplotlib` / `seaborn` (Visualization)

---

## 🚀 Installation & Usage

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/vishva2410/Anomoly-Detection-using-DBscan.git](https://github.com/vishva2410/Anomoly-Detection-using-DBscan.git)
    cd Anomoly-Detection-using-DBscan
    ```

2.  **Install Dependencies**
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn
    ```

3.  **Run the Script**
    ```bash
    python main.py
    # OR open the Jupyter Notebook
    jupyter notebook Anomaly_Detection.ipynb
    ```

---
 
