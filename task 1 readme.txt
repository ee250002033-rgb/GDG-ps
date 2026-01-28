in the task 1 of gdg aiml ps I have used amazon chronos , a model that is pretrained on various time series and is beginner friendly and works on colab and on the latest python version 3.14.

also specifically I have used chronos t5 small which is the lighter version of chronos and it gave a good accuracy of stock prices but lacked the means to predict volatility of market and is beased on the T5 architecture. 
the problem i faced in the M%M dataset was that there were commas in the stock prices which the model was not recognising and predicting a linear graph with no dips , the issue was solve by removing all commas from the prices.

i have also added a confidence interval in the predicted data which  predicts the probability of range of real data.

the data i have added is the M&M 1year stock data from 2025 to 2026
 
