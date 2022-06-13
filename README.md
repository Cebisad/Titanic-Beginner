# Titanic-Beginner
Predicting the survival rates from the titanic 
The first project predicts survival rates with the following variables as independent: Pclass, Sex, Age, SibSp, Parch, Fare and Embarkment
The model using LogisticRegression has a prediction accuracy of 0.8075842696629213 when trained and 0.7821229050279329 when tested
When the model was tested to check it's accuracy with a random passanger it accurately predicted the person's survival.

The second project removes more independent variables, leaving only the following to predict; Pclass	Sex	Age	Fare	Embarked.
The model had a prediction accuracy of 0.8089887640449438 when trained but we saw a drop in the prediction when using the test data to 0.776536312849162. It seems to suggest that the fewer independent variables there are available the less accurate the model.
When the model was tested using a random passenger it still predicted accurately. Which means the drop in acccuracy would not warrant the model inaccurate.
