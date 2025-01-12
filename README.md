# Heart-disease-predictor
A machine learning project that predicts the risk of a heart attack using SVM, Logistic Regression, and Decision Tree. It features data preprocessing, exploratory data analysis, and model evaluation. The SVM model achieved the best accuracy and is used for predictions.
# Features
Data Preprocessing: Handles missing values, scaling, and encoding of categorical features.
Exploratory Data Analysis (EDA): Analyzes feature distributions and correlations.
Model Training: Trains models using Logistic Regression, Random Forest, and SVM.
Evaluation Metrics: Accuracy, precision, recall, and F1-score to evaluate model performance.
Best Model: SVM achieved the highest accuracy and is selected as the final model.

# Model Training
SVM (Support Vector Machine): This model uses a hyperplane to classify the data. We used a linear kernel, which works well for this dataset. SVM is effective for high-dimensional data and provides a good margin of separation between the classes.

Logistic Regression: This model uses a logistic function to predict the binary outcome (heart attack or not). It’s a simpler, probabilistic model that works well for linearly separable data.

Decision Tree: A tree-based model that splits the data based on feature values to make predictions. It’s intuitive and interpretable, but it can easily overfit the training data if not tuned properly.

Gradient Boosting: Gradient Boosting is an ensemble learning method that combines multiple weak learners (decision trees) to create a strong predictive model. It iteratively fits decision trees to the residuals of the predictions, correcting errors made by the previous trees. This method is powerful and often produces high-performance models, especially on tabular data like this.

# Model Evaluation
The trained models are evaluated using common classification metrics:

Accuracy: The percentage of correctly predicted instances.
Precision: The proportion of true positive predictions to the total predicted positives.
Recall: The proportion of true positive predictions to the total actual positives.
F1 Score: The harmonic mean of precision and recall.
Based on the evaluation metrics, SVM achieved the highest performance and was selected as the final model.
