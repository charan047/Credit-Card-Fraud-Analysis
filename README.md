# Credit-Card-Fraud-Analysis

# Project Title: Credit Card Fraud Analysis and Detection using Kaggle Dataset

Link to download the dataset https://drive.google.com/file/d/13vhzyateQeZrhq2Y2hjlvrvwVQcyMgzE/view?usp=share_link

# Project Description:
The Credit Card Fraud Analysis and Detection project aims to develop an effective solution for identifying and preventing credit card fraud. The project utilizes a dataset obtained from Kaggle, which is initially cleaned and preprocessed to ensure data quality. The processed dataset is then split into training and testing sets for model evaluation.

The project begins with comprehensive exploratory data analysis (EDA) to gain insights into the dataset and understand its characteristics. EDA techniques are applied to visualize the data, identify patterns, and detect any anomalies or irregularities that may indicate fraudulent activities.

To build accurate predictive models, two different algorithms are implemented: Decision Tree Classifier and Random Forest Classifier. The models are trained on the preprocessed dataset and their performances are evaluated. To handle the class imbalance issue common in fraud detection, the Synthetic Minority Oversampling Technique (SMOTE) is employed.

Additionally, the hyperparameters of the Random Forest Regression algorithm are fine-tuned to optimize its performance. This process involves systematically adjusting the algorithm's parameters to improve its accuracy and efficiency.

Once the models are trained and optimized, the project focuses on scaling the data analysis using Apache Spark. The dataset is replicated into three replicas within a Hadoop cluster to leverage Spark's distributed computing capabilities. Spark enables efficient processing and analysis of large-scale datasets, allowing for faster insights and improved fraud detection.

Using Apache Spark, the project performs advanced data analysis techniques, including feature engineering, data transformations, and model evaluation on the replicated dataset. These techniques enhance the accuracy and effectiveness of the fraud detection models.

By combining the power of Kaggle datasets, data cleaning and preprocessing, exploratory data analysis, model comparison, hyperparameter tuning, Hadoop cluster replication, and Apache Spark's distributed computing, this project aims to provide a robust credit card fraud analysis and detection system. The results obtained from this project contribute to the development of effective fraud detection techniques and aid in protecting users against financial losses due to fraudulent activities.
