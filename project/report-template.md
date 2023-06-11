# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Nnaemeka Okeke

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Submission was not working initially when I had count prediction values that were less than zero. When the count prediction values less than zero were
equated to zero, the submission was able to go through to Kaggle.
### What was the top ranked model that performed?
TODO: WeightedEnsemble_L3 performed the best. I think it did so because it gave weight to each model used in the training based on their individual performance 

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Exploratory data analysis helped me find out that some of the columns in the dataset had datatypes that mismatched the actual kind of data which they contained. I converted the datetime column to datetime64 and that conversion allowed me to create new additional features

### How much better did your model preform after adding additional features and why do you think that is?
TODO: the previous score was -53.092194 while the score afterwards was -52.772252. I think the additional features and the conversion of the data that some of the previous features contained made the model to train better

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: the score -52.971909 which is better than the baseline model score_val of -53.092194 but not as good as -52.772252. I guess I needed to try out even more hyperparameters

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I'd make a pairplot of the features to ensure that there are no features that are too correlated.
I also think there is room for me to play around some more with some of autogluon's hyperparameters and see what that leads to. I'd still do that, but by then I should have submitted this report

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
