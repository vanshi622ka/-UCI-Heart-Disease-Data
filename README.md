# -UCI-Heart-Disease-Data
IT CONSIST Heart Disease Predictions 🤍
📊 Age Distribution:
There are 920 data points, and the average age is approximately 53.5 years, with an average difference of 9.4 years.
The youngest person is 28 years old, and the oldest is 77 years.
The majority of ages fall between 47 to 60 years.
👨‍👩‍👧 Gender Distribution:
Approximately 77.77% of individuals with heart disease in the dataset are males.
Approximately 22.22% of individuals with heart disease in the dataset are females.
❤️ Age and Heart Disease:
The age range 54-55 has the highest occurrence of heart disease.
🌍 Regional Analysis:
"In the dataset, Hungary has the highest heart disease prevalence at 32.7%, followed by Cleveland (31.7%), VA Long Beach (22.4%), and Switzerland (13.2%), considering both males and females."

Female:
Cleveland: 97
Hungary: 81
Switzerland: 10
VA Long Beach: 6
Male:
Hungary: 212
Cleveland: 207
VA Long Beach: 194
Switzerland: 113
📈 Age Statistics:
Mean Age:
Cleveland: 54.35
Switzerland: 55.32
VA Long Beach: 59.35
Hungary: 47.89
Median Age:
Cleveland: 55.5
Switzerland: 56.0
VA Long Beach: 60.0
Hungary: 49.0
Mode of Age:
Cleveland: 58
Switzerland: 61
VA Long Beach: 62, 63
Hungary: 54
💔 Chest Pain Types:
Asymptomatic: VA Long Beach (129), Cleveland, Hungary, Switzerland.
Atypical Angina: Hungary (104), Cleveland, VA Long Beach, Switzerland.
Non-Anginal: Cleveland (80), Hungary, VA Long Beach, Switzerland.
Typical Angina: Cleveland (22), Hungary, VA Long Beach, Switzerland.
🧑‍🤝‍🧑 Chest Pain by Gender:
Asymptomatic more in males (404) than females (64).
Atypical Angina more in males (110) than females (61).
Non-Anginal more in males (143) than females (52).
Typical Angina more in males (35) than females (10).
📝 Additional Information:
Unique values in different columns:
fbs: True False
restecg: 'lv hypertrophy' 'normal' 'st-t abnormality'
exang: False True
slope: 'downsloping' 'flat' 'upsloping'
thal: 'fixed defect' 'reversible defect' 'normal'
Mean values for various health indicators:
chol: 243.26
trestbps: 131.90
thalach: 137.07
oldpeak: 0.93
ca: 0.41
🔑 Key Insights:
Minimum age for heart disease is 28 years.
Peak age for heart disease is around 53-54 years.
Most cases occur at age 54-55 for both males and females.
Males constitute 78.91%, females 21.09%.
Significant variation in male numbers across regions (e.g., Hungary, Cleveland).
Highest number of individuals from Cleveland (304), lowest from Switzerland (123).
Highest number of females in Cleveland (97), lowest in VA Long Beach (6).
Highest number of males in Hungary (212), lowest in Switzerland (113).
📈 Model Performance:
LogisticRegression: Accuracy = 0.82, F1 Score = 0.82
SVM: Accuracy = 0.72, F1 Score = 0.71
DecisionTreeClassifier: Accuracy = 0.80, F1 Score = 0.80
RandomForestClassifier: Accuracy = 0.87, F1 Score = 0.87
GaussianNB: Accuracy = 0.83, F1 Score = 0.83
KNeighborsClassifier: Accuracy = 0.68, F1 Score = 0.68
GradientBoostingClassifier: Accuracy = 0.87, F1 Score = 0.87
XGBClassifier: Accuracy = 0.85, F1 Score = 0.85
AdaBoostClassifier: Accuracy = 0.87, F1 Score = 0.87
CatBoostClassifier: Accuracy = 0.86, F1 Score = 0.86
According to my insights:
GradientBoostingClassifier, RandomForestClassifier, AdaBoostClassifier all achieve the highest accuracy and F1 score of 0.87, making them the top performers for this task.
