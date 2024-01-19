# AI4Security
A Machine Learning project that compares different models and approaches using network traffic dataset.
The notebook is divided into 4 main chapters:
1. Data Preprocessing: data exploration and feature selection
2. Classification: both multi-class and binary classification, on the unbalanced dataset and on a balanced version
3. Clustering 
4. Anomaly Detection
The following models are implemented using Python:
- Classification:
  - Linear: Logistic Regression, GaussianNB, Linear SVC
  - Non-Linear: kNN
  - Ensembles: Random Forest, xGBoostClassifier
  - NNs:MLPClassifier
 

- Clustering:
  - k-Means (with t-SNE for dimensionaly reduction)
  - Agglomerative Hierarchical Clustering
  - DBSCAN

- Anomaly Detection
  -   Elliptic Envelope
  -   Isolation Forest
  -   Local Outlier Factor
