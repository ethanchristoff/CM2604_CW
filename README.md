# CM2604 - Classifying the chances of a person making a deposit

>[!important]
>The coursework specifies that we should use both a neural network and randome forest classifier to predict whether a person is to make a bank deposit or not based on the data sets provided (wheras it is to maintain an accuracy of 90% and above

The dataset provided is composed of `45211` values whereas it is composed of only `17` features. 

Of the 17 featuresL
- 9 are categorical
- 8 are numerical

Hence making it a requirement to simplify the dataset such that it may be fit into each of the two models. Having simplified the data it may then be curated to cut off the following features given the fact that they may be unneccesary:

- "Default" may be removed due the fact that it makes no sense to include it as almost all of its values are no and not yes, hence making the overall outcome not rely on it
- "Pdays" may be dropped given the fact that a majority of its values are -1 hence making it invaid in terms of affecting the outcome

There were other changes made as well, they will be mentioned in the report.

The code utilizs:

- Pandas
- Matplotlib
- Scikitlearn
- Numpy

To develop the model and curate the data to fit into the models
