## Welcome to Defaulter-Analyzer
The goal for this analysis is to predict credit card default based on transactional data. We will be using Tensorflow to build the predictive model, and t-SNE to visualize the dataset in two dimensions.

Dataset: Default of Credit Card Clients Dataset link: https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset

The sections of this analysis include:

Visualizing the Data with t-SNE.
Exploring the Data
Create and train the Neural Network
The achieved prediction accuracy is 82%


![alt text][logo1]

[logo1]: https://github.com/kbhyana/Defaulter-Analyzer/blob/master/Pictures/1.JPG?raw=true " "

# Visualizing the Data with t-SNE

t-SNE is a technique for dimensionality reduction that is particularly well suited for the visualisation of high-dimensional datasets. The technique has become widespread in the field of machine learning, since it gives the opportunity for a compelling two-dimensional “map” of a dataset. In our case we are looking for a qualitative first look on that map that will set some expectations for the prediction accuracy that we are targeting. In simple words, if our dataset 'looks' mixed, i.e. with many overlaps, we will not be disappointed if our neural network achieves an accuracy of 60-70%. Let's see!
 

![alt text][logo2]

[logo2]: https://github.com/kbhyana/Defaulter-Analyzer/blob/master/Pictures/2.JPG?raw=true " "

![alt text][logo3]

[logo3]: https://github.com/kbhyana/Defaulter-Analyzer/blob/master/Pictures/3.JPG?raw=true " "

![alt text][logo4]

[logo4]: https://github.com/kbhyana/Defaulter-Analyzer/blob/master/Pictures/4.JPG?raw=true " "


The visual reveals a rather mixed up dataset which means that we shall not expect to end up with an extremely accurate model. We shall also expect that our neural network will learn fairly fast due to the fact that the dataset looks balanced; there is a considerable amount of observed defaults in our dataset


**Code and full visualization Coming up soon here and on Github.**
