# Infosys-Stock-Price-Prediction
In this project, we can predict the stock price of the Infosys.

For this project, we collected the dataset from https://finance.yahoo.com/ . We have used 22 years of data starting from 2000-2022.

Firstly, we have applied machine learning algorithms after doing some preprocessing.
Algorithms:
1. Linear Regression : Mean squared error(MSE)= 0.0025
2. Support Vector Machine(SVR): Mean squared error(MSE)= 0.0031
3. Decision Tree Regressor: Mean Squared error(MSE)= 0.0078 
4. Random Forest Regressor: Mean Squared error(MSE)= 0.0044


Second time , we used neural networks to predict the price. we have applied LSTM(Long short term memory) which is an extension of RNN(Recurrent neural network).
![Screenshot (15)](https://user-images.githubusercontent.com/94118977/232517692-ff98ec25-792c-46e0-a1fd-4a0b7ef2062c.png)

Accuracy : 98.9%  ,loss : 1.0279e-04

Third Time , we applied bi-lstm(Bidirectional Long short term memory) extension of LSTM    loss: 8.3488e-05 
![Screenshot (14)](https://user-images.githubusercontent.com/94118977/232518232-aba7a7f3-1ff9-4880-9dec-2a63ae88c2eb.png)
![Screenshot (13)](https://user-images.githubusercontent.com/94118977/232518261-868480ee-7945-4713-9d48-00aa35d61de0.png)
