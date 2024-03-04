# Project Title
Binary Classification task

### Task
Given medical attributes of various patients, predict whether the patient has heart disease or not.


### Dataset
The dataset consists of various medical attributes of various patients. The dataset was obtained from the UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/45/heart+disease
##### Features:
* age: age in years
* sex: 1 = male; 0 = female)
* cp: chest pain type
* trestbps: resting blood pressure
* chol: serum cholesterol in mg/dl
* fbs: fasting blood sugar > 130 mg/dl (1 = true; 0 = false)
* restecg: resting electrocardiographic results
* thalach: maximum heart rate achieved
* exang: exercise induced angina (1 = yes; 0 = no)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed; 7 = reversable defect
#### Target:
* 0 - does not have heart disease
* 1 - has heart disease


### Models, methods, and results
* Models used:
  * KNearestNeighbors Classifier
  * Random Forest Classifier
  * Logistic Regression
  * Gradient Boosting Classifier
  * CatBoost Classifier
* Evaluation metrics:
  * Accuracy
  * Precision
  * Recall
  * F1 score
  * AUC score
* Results:
   * Accuracy: 89%
   * AUC score: 93
