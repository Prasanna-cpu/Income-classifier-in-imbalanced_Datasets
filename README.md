# Income-classifier-in-imbalanced_Datasets
We use 7 different Machine learning algorithms to classify income (binary classification) in the adult census dataset. Those are 
         1) Logistic Regression
         2) KNN Classifier
         3) Decision Tree Classifier
         4) Random Forest Classifier
         5) SGD Classifier
         6) Adaptive Boosting Classifier
         7) Gradient Boosting Classifier

# About the dataset
This dataset is available in popular public repositories such as Kaggle and UCI. Based on the given input features, we predict whether the income of an individual is below 50K (<=50K) or above 50K (>50K). This is an imbalanced dataset with nearly 75% of the instances falling in the hostile(negative) class(<=50K) and 25% of them falling in the positive class (>50K). Since this is an imbalanced dataset, we use special cross-validation techniques and more compatible accuracy metrics.

# Cross-Validation Techniques
Cross-validation is an essential technique in machine learning for assessing the performance and generalization ability of a model. It helps in estimating how well a model will perform on unseen data by simulating the real-world scenario of training and testing on different data sets.

Since this is an imbalanced dataset, we use the Repeated Stratified K Fold technique instead of the normal K fold technique. Repeated Stratified K-fold cross-validation is particularly useful in the context of imbalanced classification problems where the distribution of classes is skewed, meaning one class has significantly fewer instances than the others. It combines the benefits of both stratified sampling and repeated cross-validation to ensure robust evaluation of models.

# Hyperparameter Optimization
We use Grid search with cross-validation to determine optimal hyperparameters for all 7 models.

# Results

The accuracy metrics used here are Accuracy, Balanced Accuracy, Mean CV Score, Precision, Recall, AUC Score

The Gradient Boosting Classifier gives the best results in all the metrics

For more information, kindly refer to the notebook.

Happy Coding 🤞😊








