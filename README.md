This project aims to predict breast cancer using several machine learning classification models. The dataset used is the Breast Cancer Wisconsin Diagnostic dataset from the UCI repository, containing features extracted from digitized images of breast cell nuclei.

The Jupyter notebook walks through loading and exploring the data, preprocessing steps like handling missing values and converting categorical features to numeric.Baseline models including Logistic Regression, SVM, Naive Bayes, and Random Forest are implemented using Scikit-Learn. The models are evaluated and compared using accuracy, precision, recall, and ROC AUC metrics.

Key techniques employed include data preprocessing, hyperparameter tuning using GridSearchCV, and cross-validation to combat overfitting. Visualizations including correlation plots and confusion matrices provide additional insight into model performance.

The random forest classifier achieved the best performance with 95% accuracy on the test set. This end-to-end implementation serves as a guide for applying core machine learning concepts to classify and predict breast cancer from medical imaging data.
