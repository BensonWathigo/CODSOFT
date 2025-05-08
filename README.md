# CODSOFT

Iris Flower Classification Project
Machine Learning Model to Classify Iris Species

🔹 Project Goal: Built a machine learning model to classify iris flowers into three species (setosa, versicolor, virginica) based on their sepal and petal measurements.

🔹 Dataset: The famous Iris dataset containing 150 samples with four features:

sepal_length, sepal_width

petal_length, petal_width

📌 Key Steps & Techniques
1. Data Exploration & Preprocessing
✔ Checked for missing values (none found)
✔ Visualized feature distributions using seaborn.pairplot()
✔ Split data into train (80%) and test (20%) sets

2. Model Training & Evaluation
✔ Random Forest Classifier (Achieved 100% accuracy)
✔ Logistic Regression (Achieved 100% accuracy)
✔ Support Vector Machine (SVM) & k-Nearest Neighbors (k-NN) for comparison

📊 Performance Metrics:

Classification reports (precision, recall, F1-score)

Confusion matrices

Feature importance analysis

3. Key Findings
Petal measurements were more important than sepal measurements for classification.

The dataset was linearly separable (Logistic Regression performed as well as the ensemble methods).

Random Forest provided the best accuracy with minimal tuning.

🛠️ Technologies Used
Python (pandas, NumPy, scikit-learn)

Data Visualization: Matplotlib, Seaborn
