# Gold Price Forecasting using LSTM Recurrent Neural Networks 💰📈
This project focuses on forecasting gold prices in USD for a gold trading company to help optimize trading strategies and future investments. By providing accurate predictions, the company can decide the best times to buy or sell gold, reducing risks and boosting profits. Being able to forecast price movements up to 14 days ahead offers a valuable advantage in the often unpredictable gold market.

The dataset contained daily gold prices in six currencies (USD, EUR, GBP, INR, AED, CNY) from 1985 to 2023. These currencies reflect global market trends and factors that influence gold prices, allowing the model to capture a wide range of economic influences.

A Long Short-Term Memory (LSTM) based Recurrent Neural Network (RNN) was built to predict the next 14 days of gold prices by looking at the previous 50 days of data. The best model used 150 LSTM units, 1 hidden layer, 100 hidden nodes, and 50 number of steps; balancing complexity and performance.

Several experiments were conducted by adjusting the number of LSTM units, hidden layers, hidden nodes, and number of steps. The model's accuracy was measured using Mean Absolute Error (MAE).

The top-performing model (RNN 4) achieved an average MAE of 14.306 USD over the 14-day forecast period, with the lowest error being 10.93 USD on Day 1 and the highest at 19.22 USD on Day 9. The model handled short-term trends effectively, though it showed slight deviations during more volatile periods. Overall, its performance was strong enough to support informed trading decisions.
