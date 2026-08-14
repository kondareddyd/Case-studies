# Diabetes and BEED Classification

This project compares **Random Forest** and **K-Nearest Neighbours (KNN)** classification models on two healthcare datasets.

## Datasets
- **Diabetes 130-US Hospitals:** 101,766 records and 50 columns, with `readmitted` as the target.
- **BEED:** 8,000 records and 17 columns, with 16 EEG features and a four-class target.

## Methods
The data was preprocessed, split into training and testing sets, and scaled where required. Random Forest and KNN were evaluated using accuracy, precision, recall and Macro F1-score. Different K values were also tested for KNN.

## Result
KNN performed best on the **BEED** dataset, while Random Forest performed better on the **Diabetes** dataset.

## Files
- `s4182304.ipynb` – analysis and model implementation
- `README.md` – project information
