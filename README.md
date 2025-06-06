# Breast Cancer Diagnosis Classification using K-Nearest Neighbors (KNN) 
## Project Objective
This project applies the K-Nearest Neighbors (KNN) algorithm to classify breast cancer diagnoses as malignant or benign based on clinical features. The model is trained and evaluated using a labeled dataset to assist in early detection and decision-making in medical diagnostics.
## Data Used
- <a href="https://github.com/redwan011235/Machine-Learning-Project/blob/main/Dataset%20of%20Breast%20Cancer%20Diagnosis%20Classification%20using%20K-Nearest%20Neighbors%20(KNN).csv">Dataset</a>
## Tools Used
- NumPy
- Pandas
- Matplotlib
- Seaborn
- jupyter notebook
- Scikit-learn
## Project Workflow
- Load the breast cancer dataset using Pandas.
- Preprocess the data by handling missing values and scaling features.
- Split the dataset into training and testing sets.
- Train a K-Nearest Neighbors (KNN) classifier on the training data.
- Evaluate the model using accuracy, confusion matrix, and classification report.
- Optionally tune the value of k using GridSearchCV.
- Visualize model performance and save the final model if needed.
## Analytical Focus Areas
- Diagnosis Classification: Predict whether a tumor is benign or malignant using clinical features.
- Feature Importance Analysis: Explore which features (e.g., radius, texture, symmetry) most influence the diagnosis.
- Data Distribution Insights: Visualize the distribution of features across benign and malignant classes.
- Correlation Analysis: Examine relationships between features to identify multicollinearity or patterns.
- Model Performance Evaluation: Assess accuracy, precision, recall, and F1-score of the KNN classifier.
- Hyperparameter Impact: Analyze how different values of k affect classification accuracy.
##  Project Insight
- The KNN model achieved an overall classification accuracy of approximately 96% on the test dataset.
- Benign and malignant tumors were successfully classified using only ten selected clinical features.
- The classification report showed high precision and recall values, especially for the malignant class, which is critical for medical reliability.
- StandardScaler preprocessing helped improve model accuracy by normalizing feature scales.
- The model maintained robust performance with minimal false negatives, which is vital for early detection of cancer.
- K=5 was used for KNN, yielding a balance between underfitting and overfitting.
- The pipeline includes proper data cleaning, handling of missing values, and model evaluation using classification_report and confusion_matrix.

