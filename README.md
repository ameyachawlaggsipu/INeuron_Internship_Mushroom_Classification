# Mushroom Classification Project
![d41586-019-03614-0_17409632](https://user-images.githubusercontent.com/88154798/139305607-2f5e5048-4adb-4556-82c3-63c9d210a4d6.jpg)

## Problem Statement:
<p>The Audubon Society Field Guide to North American Mushrooms contains descriptions
of hypothetical samples corresponding to 23 species of gilled mushrooms in the
Agaricus and Lepiota Family Mushroom (1981). Each species is labelled as either
definitely edible, definitely poisonous, or maybe edible but not recommended. This last
category was merged with the toxic category. The Guide asserts unequivocally that
there is no simple rule for judging a mushroom's edibility, such as "leaflets three, leave it
be" for Poisonous Oak and Ivy.
The main goal is to predict which mushroom is poisonous & which is edible.</p>

## Approach used
<p>The main goal of this project is to classify whether the Mushroom is Edible or Poisonous </p>

->> Data Analysis        : I started Analysing dataset using pandas,seaborn, and sklearn. 

->> Data visualization   : Plotted t-SNE plot to get clear idea of separation of classes and gain more knowldegw how class elements are clustered. 

![2dScalar Diagram](https://user-images.githubusercontent.com/88154798/139250275-1d7c3308-b49e-47b7-8bce-c0bc8f668fba.png)

->> Evaluation Metric    : Accuracy was used with K-Fold Cross Validation of 10 folds.

->> Model Selection      : Tested Machine Learning Models with gridsearch technique and compared average accuracy obtained in K-Fold Cross Validation .

![Accuracies](https://user-images.githubusercontent.com/88154798/139250588-6e7b942a-f813-44b2-9f63-46db762a16a4.png)

->> Pickle File          : Selected model as per best accuracy and created pickle file using joblib (Random Forest max depth 72 performed best with average accuracy= 0.9655560200922206 .

## Home Webpage 
<p>Webpage to upload .csv file</p>

![Screenshot (1445)](https://user-images.githubusercontent.com/88154798/139388983-f5db7144-0550-4ccb-8b72-8cfd304bf109.png)

## Prediction Webpage 
<p>Showing results and home button to go back to home page</p>

![Screenshot (1446)](https://user-images.githubusercontent.com/88154798/139389101-b11a5bf1-dad6-4e72-a3e6-51583c4e2881.png)

## Deployment
Web app is deployed using Heroku services.
https://mushroomclassifier99.herokuapp.com/
