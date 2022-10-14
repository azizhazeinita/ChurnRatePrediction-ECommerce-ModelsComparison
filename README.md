# ChurnRatePrediction-ECommerce-ModelComparison

*A personal project by Azizha Zeinita*

* **Project Goal**: 

The purpose of this project is to find **customer churn rate prediction in e-commerce** dataset. This approach is used to detect which features affect churn rate, so that company can use it to do future forecasting to **predict which customers who tend to leave the service** and make **promotion strategy** to offer.


* **Dataset**:
  * The data set belongs to a leading online E-Commerce company that's posted in https://www.kaggle.com/code/wonderdavid/e-commerce-customer-churn-prediction/data
  * Dataset is splitted into:
       * Train (Splitted into train and validation via GridSearchCV)
       * Validation (Part of initial splitted train dataset via GridSearchCV)
       * Test


* **Methods**: 
  Using GridSearchCV 5 folds and pipeline for 6 kinds of model with different kind of parameters:
   * Linear Classifier:
       * Logistic Regression
       * Naive Bayes
       * SVM
    * Tree Classifier:
      * DecisionTreeClassifier
      * RandomForestClassifier
      * XGBClassifier
