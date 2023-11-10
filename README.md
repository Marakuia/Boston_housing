# Boston_housing

In this work, a neural network was implemented to solve a regression problem - predicting house prices in Boston based on 13 characteristics. The neural network was implemented using the keras library. K-fold cross-validation was also implemented. The influence of the number of epochs and the number of folds on network overfitting was investigated. <br/>

RMSprop was used as the optimizer, root mean square error (MSE) was used as the loss function, and mean absolute error (MAE) was used as the evaluation metric. <br/>

Below are graphs of losses and mae for different numbers of epochs: 50, 100 and 200, respectively. <br/>
![Image alt](https://github.com/Marakuia/Boston_housing/blob/main/result/epochs.png) <br/>

Below are graphs of the loss function and mae depending on the number of folds: 2, 4 and 8, respectively. <br/>
![Image alt](https://github.com/Marakuia/Boston_housing/blob/main/result/folds.png) <br/>
