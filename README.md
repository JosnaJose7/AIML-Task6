# AIML-Task6
# K-Nearest Neighbors (KNN) Classification on Iris Dataset

## Project Overview
The project illustrates the application of the K-Nearest Neighbors (KNN) classification algorithm utilizing the Iris dataset. The objective is to learn the functioning of KNN, test various K values, monitor model performance, and display decision boundaries.

## Dataset
- **Name:** Iris Dataset
- **Source:** `/content/Iris.csv` (widely available from UCI Machine Learning Repository)
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target:** Species (Setosa, Versicolor, Virginica)

## Tools and Libraries
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Steps Performed
1. **Data Loading:** Loaded the Iris dataset from a CSV file.
2. **Data Preprocessing:** Removed redundant columns and normalized features with `StandardScaler`.
3. **Train-Test Split:** Split the dataset into training and test sets with stratification to preserve class balances.
4. **Model Training & Evaluation:** Trained KNN classifiers with varying values of K (1, 3, 5, 7, 9), tested accuracy, and printed confusion matrices.
5. **Visualization:** Plotted decision boundaries of the best performing KNN model with the first two features for easier plotting.

## How to Run
1. Upload `Iris.csv` to your Google Colab environment or make sure it is at `/content/Iris.csv`.
2. Run the given Python script within a Colab notebook.
3. Note printed accuracy scores, confusion matrices, and decision boundary plots.

## Key Learnings
- Role of feature scaling in KNN.
- Impact of varying K values on model performance.
- Application of confusion matrix to classify results.
- Visual insight of decision boundaries in classification.
