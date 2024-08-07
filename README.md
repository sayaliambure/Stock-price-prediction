# Stock-price-prediction

Takes stock prices data of companies and predicts stock prices based on features like open/close stock price, high/low stock price for the day.

LSTM is used for training of model for analyzing stock market data because it can handle data with multiple input and output timesteps. LSTMs are a type of RNN that remember information over long periods of time


## EDA on Microsoft stock data:

--> Mean and standard deviation of high prices

![Screenshot 2024-06-29 232029](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/4ba5141f-0791-44b3-86f6-7703893fe7fb)


--> Mean and standard deviation of close prices

![Screenshot 2024-06-29 233101](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/439c6544-83c4-4c08-bf9a-66ace430acbf)


--> Analysis of the Volume Data on Daily, Monthly, and Yearly Basis

![image](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/48df0792-edfa-4e3e-8441-ad8885840d38)



--> Dependency of adjusted closing prices with daily high prices

![Screenshot 2024-06-29 231719](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/5dca9402-6f9b-4146-bab2-48042366ad20)




## Results after training model using LSTMs: 
--> True vs Predicted stock value

![Screenshot 2024-06-29 233258](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/b752d4bc-4f6f-4037-bbdf-89e648ffa186)


-->  Moving average of last 100 predixtions

![Screenshot 2024-06-29 233401](https://github.com/sayaliambure/Stock-price-prediction/assets/89408981/88fff2bc-456d-4107-9b54-6589b078ee6e)




