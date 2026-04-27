# Athlete-s-Injury-Prediction

The Football Injury Prediction System is a machine learning-based application designed to predict the likelihood of injuries in football players using historical and physiological data. By leveraging the power of ensemble learning through a Random Forest Classifier, the system provides accurate and interpretable predictions that can assist coaches, analysts, and medical teams in proactive decision-making.

## About the dataset
File: football_injury_dataset.csv
Type: Structured CSV dataset
Target Variable: injury (0 = No Injury, 1 = Injury)


## Performance Metrics
```
Model Accuracy: 96.75%
Classification Report:
               precision    recall  f1-score   support

           0       0.96      0.97      0.97       196
           1       0.97      0.97      0.97       204

    accuracy                           0.97       400
   macro avg       0.97      0.97      0.97       400
weighted avg       0.97      0.97      0.97       400
```
## Confusion Matrix
```
[[190   6]
 [  7 197]]
```
## Features and Their Importance
Jump Height            0.198303  
BMI                    0.095379  
Game Intensity         0.092089  
Previous Injuries      0.090575  
Player Speed           0.081763  
Player Acceleration    0.066139  
Sprint Time            0.064681  
Endurance              0.059107  
Agility                0.057191  
Playing Time           0.057066  
Fatigue                0.050431  
Reaction Time          0.049244  
Strength               0.014143  
Training Load          0.012615  
Weather Impact         0.011273  
dtype: float64  
Injury                 1.000000  
Game Intensity         0.338830  
Player Speed           0.337192  
Endurance              0.323241  
BMI                    0.293528  
Player Acceleration    0.232926  
Fatigue                0.040867  
Weather Impact         0.023780  
Playing Time           0.006394  
Training Load          0.004187  
Reaction Time         -0.007162  
Strength              -0.009382  
Agility               -0.318126  
Previous Injuries     -0.327552  
Sprint Time           -0.407131  
Jump Height           -0.619461  
Name: Injury, dtype: float64  