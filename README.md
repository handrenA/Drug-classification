# Multi-Drug classification
This is a multi-classification problem where we predicting what drug is the most suitable for a patient based on their, 

* Age
* Sex
* Blood Pressure Levels
* Cholesterol Levels
* Na to Potassium Ratio


After doing EDA and feature engineering - the final conclussion on the analysis was that the age actaully does not have a impact on what drug is the most suitable
for a patient. However the most important feature is Na to Potassium Ratio which is kind of obvious because potassium and sodium are electrolytes needed for the body to function normally and help maintain fluid and blood volume in the body. However, a person can get high blood pressure by consuming too much sodium and not enough potassium. Thus, this criteria is considerably important while constructing the ML model.

## Algorithms & score 
Hyperparameter tuning on RandomForestClassifier gave final evaluation on the test data to be 100% when accuracy score were used, however 
this does not mean that the model is perfectly fitted and should therefore keep their mind that the data _may_ be overfitted.

