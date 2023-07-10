# Crop_Price_Prediction

DATASET DESCRIPTION:
The dataset provides total information of 23473
surveys dating as back as 1866. All surveys were
done state-wise, and we will focus on the corn
grain. It is summarized by a value for each study
corresponding to the state.
The second dataset contains features for various
crops and we have applied the best algorithm to
make sure most accurate predictions for the same.

![image](https://github.com/Mufid-Vahora/Crop_Price_Prediction/assets/77350851/1a7519c9-0796-492b-8175-6a205d35abe5)


NOVELTY:
We have used one hot encoding here. One hot
encoding is a technique used in data
preprocessing to represent categorical variables
as numerical values, which can be used as input
for machine learning algorithms.
We have implemented this on 3 data frames from
the dataset. Period, Data Item, and State.

We have also compared the metrics for all models
possible, to find the best fit according to our
dataset, and can conclude that Random Forest
Regressor gives us the best R2 value.

![image](https://github.com/Mufid-Vahora/Crop_Price_Prediction/assets/77350851/99b9703b-8a8b-4ad0-8315-f5b7c75c6e2d)

Following up on this we used the same random
forest regressor on a larger dataset containing
different crops, to make sure it follows through.
