# Naive Bayes Classifier Evaluation

## Project Overview

This project implements the Naive Bayes classification algorithm and evaluates its performance on three distinct datasets: Hayes-Roth, Car, and Breast Cancer. The project focuses on data preprocessing, handling missing values, mapping categorical data to numerical values, and using cross-validation to assess the classifier's accuracy.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)

## Datasets

1. **Hayes-Roth Dataset**: Contains attributes related to demographic information and class labels.
2. **Car Dataset**: Includes attributes related to car evaluations and class labels.
3. **Breast Cancer Dataset**: Consists of attributes related to breast cancer diagnoses and class labels.

## Prerequisites

- Python 3.6 or higher
- Libraries: pandas, numpy, matplotlib

## Usage

1. Prepare your datasets (CSV format) and place them in the project directory.
2. Run the Jupyter Notebook to execute the project:
   ```sh
   jupyter notebook naive_bayes_classifier_evaluation.ipynb
   ```

## Project Structure

- `naive_bayes_classifier_evaluation.ipynb`: Jupyter Notebook containing the implementation and evaluation of the Naive Bayes classifier.
- `hayes-roth.csv`: Hayes-Roth dataset.
- `car.csv`: Car evaluation dataset.
- `breast-cancer.csv`: Breast cancer dataset.
- `README.md`: Project documentation.

## Results

The project evaluates the Naive Bayes classifier using cross-validation and visualizes the accuracy scores for each dataset. The results demonstrate the effectiveness of data preprocessing and the classifier's performance on different types of data.

### Example Results

#### Hayes-Roth Dataset
- Mean Accuracy: 79.82%

#### Car Dataset
- Mean Accuracy: 87.56%

#### Breast Cancer Dataset
- Mean Accuracy: 73.16%

---

Feel free to adjust any sections as needed to better fit your project specifics.
