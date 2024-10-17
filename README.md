# PCA_Breast_Cancer

This repository contains a Jupyter Notebook implementing Principal Component Analysis (PCA) on the Breast Cancer Dataset.

## Steps

1. **Data Loading**: We load the dataset `breast_cancer_data.csv`.
2. **Data Preprocessing**:
   - Drop unnecessary columns (`id` and `Unnamed: 32`).
   - Replace the `diagnosis` column with binary labels (0 for benign and 1 for malignant).
   - Standardize the dataset using `StandardScaler`.
3. **PCA Application**:
   - Apply PCA to reduce the dataset's dimensionality to 2 components.
   - Plot the resulting PCA components, colored by the diagnosis label.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pca-breast-cancer.git

2.	Install the required dependencies:
```
pip install pandas numpy matplotlib scikit-learn
```

 3.	Run the notebook pca_breast_cancer.ipynb to see the PCA implementation.

Dependencies

	•	Python 3.x
	•	Pandas
	•	Numpy
	•	Matplotlib
	•	Scikit-learn
