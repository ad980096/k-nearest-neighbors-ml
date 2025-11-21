# k-nearest-neighbors-ml
K-Nearest Neighbors (KNN) classification project implemented using Python. Includes data preprocessing, feature normalization, experimenting with different K values, evaluating performance using accuracy and confusion matrix, and visualizing decision boundaries using PCA.
Overview:This project demonstrates how to build a K-Nearest Neighbors (KNN) classifier for a classification dataset. It includes data normalization, experimenting with different K values, accuracy evaluation, and decision boundary visualization.
 Tools Used
Python
Pandas
Scikit-learn
Matplotlib

 Steps Performed
1️. Load & Prepare Dataset

Used a classification dataset (e.g., Iris dataset).

Split dataset into train and test sets.

Normalized features using StandardScaler.

2️. Train KNN Classifier

Trained KNN using multiple values of K.

Selected the best K based on test accuracy.

3️. Evaluate Model

Generated accuracy, confusion matrix, and classification report.

Compared accuracy across different K values.

4️. Visualize Decision Boundaries

Used PCA to reduce data to 2D.

Plotted approximate KNN decision boundaries.

 Results

KNN accuracy varies with the value of K.

Normalization significantly improves performance.

Decision boundary plot helps visualize class separation.

 How to Run
Install dependencies:
pip install pandas numpy scikit-learn matplotlib

Run the Python script or Jupyter Notebook to:
Train the KNN model
Test different K values
View accuracy, confusion matrix, and visualizations
