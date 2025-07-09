The credit card fraud detection dataset from Kaggle was used, starting with data cleaning and exploratory analysis to understand its structure.
Supervised models like Random Forest and XGBoost were applied to predict fraud, evaluated using metrics such as precision, recall, and F1-score.
Due to class imbalance and challenges in obtaining accurate labels, a shift to an unsupervised approach was made by removing the class column.
In this new approach, the Isolation Forest model was used to detect anomalies based solely on data behavior.
