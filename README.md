# Neural Network Recommender
Neural Network Recommender for Recommending the Best Possible Hotel Stay
<hr>
The Aim of this project was to create a neural network recommender which, for given users, would recommend the best possible hotel stays. The main goal was to beat Amazon's recommender which was trained on the same dataset.

## Preparing data 
The <code>users_df</code> dataframe was one-hot encoded, and the user features were normalized by calculating the probability for each value.
On the other hand, the <code>items_df</code> dataframe was only one-hot encoded

## Neural Networks
Recommender can use two of the avaiable Neural Networks:<br>
-<b>MyDropoutNet:</b> This neural network is designed with a main feature of a dropout layer, along with a single ReLU layer.<br>
-<b>MyHiddenNet:</b> This neural network is characterized by two hidden layers.

There were plans to create a neural network with embedding layers but I wasn't able to do it.

## Tuning
