# IMDB Movie Dataset - Prediction and Analysis

This project is about performing a comprehensive analysis of IMDB movie dataset to predict the success rate of movies using popular machine learning concept and then comparing the results. Visualisation in various perspectives to anaylse the trend is also under the scope of this project. The project uses the following models
1. K-nearest neighbour.
2. AdaBoost
3. SVM(Support Vector Machine)
4. Naive Bayes Classifier
5. Logistic Regression 

All models are from sklearn library. The data cleaning process has been perfomed only once and cleaned dataset is used for the complete analysis. Each Model's performance has been calculated in terms of 

  - Confusion Matrix.
  - Accuracy.
  - Precision.
  - Recall.
  - ROC(Receiver Operating Characteristics) and AUC(Area Under the Curve).

### Installation

The application use python for data processing and sklearn library for machine learning models.
To make it work in your local machine you can use either jupitur Notebook or standalone python version.
To read the analysis and comparison study report you just need a pdf reader, the Microsoft Word version of the same is also available.

### Usage

```
from sklearn.linear_model import LinearRegression

predictor = LinearRegression(n_jobs=-1)
predictor.fit(X=TRAIN_INPUT, y=TRAIN_OUTPUT)

X_TEST = [[10, 20, 30]]
outcome = predictor.predict(X=X_TEST)
coefficients = predictor.coef_

print('Outcome : {}\nCoefficients : {}'.format(outcome, coefficients))
```    

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-analysis`
3. Commit your changes: `git commit -am 'Add some analysis'`
4. Push to the branch: `git push origin my-new-analysis`
5. Submit a pull request :D

License
----

**Free, Hell Yeah!**