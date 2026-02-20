📊 Predicting the Success of Bank Telemarketing Campaign


This project predicts whether a customer will subscribe to a term deposit using data from a bank telemarketing campaign.

The goal is to apply Machine Learning techniques to improve marketing efficiency and help financial institutions target high-probability customers more effectively.

🎯 Objective

To build and compare multiple classification models in order to:

Improve campaign targeting

Reduce marketing costs

Increase conversion rates

Identify high-value customers

🛠️ Project Workflow
📌 1. Library Imports

Imported essential libraries such as Pandas, NumPy, Scikit-learn, LightGBM, XGBoost, Matplotlib, and Seaborn.

📌 2. Data Extraction

Loaded and inspected the dataset.
Checked structure, data types, and initial observations.

📌 3. Dummy Classifier (Baseline)

Implemented a baseline model to establish benchmark performance before training advanced models.

📌 4. Exploratory Data Analysis (EDA)

Feature distribution analysis

Correlation analysis

Outlier inspection

Business-level pattern identification

📌 5. Comparison with Target

Analyzed how key features influence the subscription outcome.

📌 6. Target Distribution Analysis

Identified class imbalance in the dataset.

📌 7. Imputation

Handled missing values appropriately.

📌 8. Preprocessing & Feature Engineering

Categorical encoding

Feature scaling

Feature transformation

Train-test split

📌 9. Model Training

Trained multiple models:

Logistic Regression

XGBoost Classifier

LightGBM Classifier

📌 10. Hyperparameter Tuning

Performed tuning for:

LightGBM

XGBoost

📌 11. Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1 Score

Since the dataset is imbalanced, Macro F1 Score was considered the primary evaluation metric.

📊 Model Comparison
Model	Accuracy	Macro F1 Score
Logistic Regression	0.85	0.69
XGBoost (Tuned)	0.86	0.77
LightGBM (Tuned)	0.85	0.76

After comparison, Tuned LightGBM performed comparatively best across evaluation metrics.

📈 Final Model Performance

Selected Model: Tuned LightGBM Classifier

Accuracy: 85%

F1 Score (Macro Avg): 0.76

Precision (Macro Avg): 0.73

Recall (Macro Avg): 0.83

📌 Due to class imbalance, Macro F1 Score was prioritized over accuracy.

The model achieved strong recall (0.80) for subscribed customers, making it suitable for identifying potential leads in marketing campaigns.

🚀 Result

The tuned LightGBM model significantly outperformed the baseline model and provided balanced performance across both classes.

Logistic Regression struggled due to linear assumptions.
XGBoost performed well, but LightGBM provided better macro F1 score and recall for the minority class due to its leaf-wise growth strategy and efficiency with high-dimensional data.
Therefore, LightGBM was selected as the final model.

This model can help financial institutions:

Focus on high-probability customers

Reduce unnecessary calls

Improve campaign ROI

Increase subscription conversion rate

👤 Author

Jibin Aloysious K J

IIT Madras – Data Science
