# Cancer Classification using SVM

This project demonstrates the use of **Support Vector Machines (SVM)** to classify human cell samples as either benign or malignant based on a dataset of cell characteristics.

## Project Overview

The project involves:
- **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
- **Modeling**: Building an SVM model using various kernels, including **RBF** and **Linear**.
- **Evaluation**: Assessing the model's performance using metrics such as accuracy, F1-score, Jaccard index, and confusion matrix.
- **Visualization**: Plotting decision boundaries for the linear kernel to better understand model behavior.

## Dataset

The dataset is publicly available from the **UCI Machine Learning Repository**. It contains several hundred records of human cell samples, with features such as:
- Clump Thickness
- Uniformity of Cell Size
- Uniformity of Cell Shape
- Bare Nuclei
- Bland Chromatin
- Mitoses

The target variable is:
- `2` for **Benign**
- `4` for **Malignant**

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/IpsitMohanty/Cancer-Classification-SVM.git
