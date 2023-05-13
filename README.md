# NP-ARX for Bulb Weight Prediction

I appreciate your notification regarding the supporting paper titled "Advancing Agricultural Predictions: A Deep Learning Approach to Estimating Bulb Weight Using Neural Prophet Model." 
The provided link leads to the download page-https://www.mdpi.com/2073-4395/13/5/1362


# Model Performance Notification

From the beginning, the model has been built manually setting for hidden layer and dimension
However, From now on, hyperparameter 'num_hidden_layer' and 'd_hidden' is not serviced in Neural Prophet.
Nevertheless, NP-ARX successfully and automatically, makes it possible to flow AR-NET for input data.

MAE, RMSE is slightly enhanced, compared with the result in the paper
In Onion: MAE(test) 4.66 -> 3.72g  / RMSE(test) 8.68 -> 8.09g

I am sure that the NP model set optimal AR-NET structure, I wish you are happy to explore the NP-ARX model for Crop Yield prediction!!
