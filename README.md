
## Relax Inc Challenge
A take home data science challenge from Relax Inc. (anonymized real company). Provided by Springboard Data Science Career Track.

### Analysis
I analyzed user retention data of a of Relax, Inc. I also found which factors that were important to creating user retention. Here is what I found:

1. 
![image](https://user-images.githubusercontent.com/86930309/218946378-36d4b5f5-3516-4e93-943f-cab7cd259e39.png)

The accounts that were created as a full member were more inclined to to be an adopted user than any other type that was created.

2.
![image](https://user-images.githubusercontent.com/86930309/218946472-6e2d7ce6-f63a-4941-9606-c553681075f8.png)
The highest positive correlation was "enabled for marketing drip" and "opted into mailing list" at .48.

3. Grid Search CV for Random Forest Classifier
GridSearchCV(estimator=RandomForestClassifier(class_weight='balanced',
                                              min_samples_split=3,
                                              random_state=42),
             param_grid={'n_estimators': [10, 50, 100, 200]})
An average of .6655 from the Grid Search CV.

### File structure
- The questions can be found in the [Directions](https://github.com/GHASS19/GHASS19-Take-Home-Challenge-Relax-Inc-/blob/main/Relax%20Directions.pdf)
- The python code and graphs are in [Take Home Challenge Relax](https://github.com/GHASS19/GHASS19-Take-Home-Challenge-Relax-Inc-/blob/main/Relax%20Inc.%20Take-Home%20Challenge.ipynb) 
