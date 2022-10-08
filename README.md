
# Titanic Tutorial - Kaggle Challenge 



This is a blog about my first kaggle challenge. 
This challenge contains the data of the passengers on the titanic ship and we want to predict who will survive and who will not in the test.csv dataset by learning the patterns from the train.csv dataset. I have done this by using a machine learning algorithm.  


## Data

There are 891 data points in the train.csv and 418 in the test.csv. 
There is a column called 'Survived'in train data that determies whether a 
person survived or not. The same column is absent in test dataset and our goal is to 
accurately predict the same values in test dataset. 


## Flow of the python notebook

First I loaded the train and test datasets into pandas dataframe. 
Then I found the percentage of males and females that survived 
the sinking ship based on the data in train.csv. 
Around 74% females survived and 18% males survived the ship. 
From this we can conclude that the gender is a very significant parameter for the prediction. 

After that I ran a ML model that is Random forest classifier,
 which uses multiple decision trees and makes the prediction. 
 The parameters that I used for my classifier are Pclass, Sex, 
 SubSp & Parch. I increased the n_estimators parameter from 100 to 
 250 which determines the number of trees that the classifier will generate. 


## References

The code used in this repository is taken from kaggle challenge walk-through. 

[Titanic Tutorial](https://www.kaggle.com/code/alexisbcook/titanic-tutorial/notebook)

