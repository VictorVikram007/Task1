#  Task 1: Data Cleaning & Preprocessing – AI & ML Internship

##  Objective
The goal of this task is to clean and preprocess raw data to make it suitable for machine learning models. The Titanic dataset from Kaggle was used for this exercise.

##  Dataset
- Source: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `titanic.csv`

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

##  Steps Performed
1. Imported dataset and explored structure using `.info()` and `.describe()`.
2. Handled missing values:
   - Filled `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped `Cabin` due to excessive missing values.
3. Encoded categorical features:
   - Converted `Sex` to numeric using label encoding.
   - Applied one-hot encoding to `Embarked`.
4. Normalized `Age` and `Fare` using StandardScaler.
5. Visualized and removed outliers in `Fare` using IQR method.
6. Saved the cleaned dataset as `titanic_cleaned.csv`.

##  Visuals
Boxplots were used to visualize outliers in the `Age` and `Fare` columns.

##  Output
A cleaned version of the dataset, ready for machine learning, saved as:

##  Repository Contents
- `titanic.csv`: Raw dataset (optional if not uploading)
- `titanic_cleaned.csv`: Final cleaned dataset
- `task1_cleaning.ipynb`: Colab notebook or Python file
- `README.md`: Task explanation (this file)
- `Task1-Output.png`: It shows the output of the task


