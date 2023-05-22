# Stock-Market-Analysis-Time-Series-
In this Project we have analyised previous years data of a company(Reliance) and with past performances, growth rate we have built a predictive model which will predict stock price for next 30 days.
With trends in the market from past few years which have an effect on stock price, we tried to analyize stock's performance.We have performed EDA by cleaning the data extracted from yfinance module in python and removed some unwanted features. With correlation of the features we have concluded final stock price as the final target variable on which models have to be built and predict. 
And to be sure of it we have done some Auto EDA techniques as well such as 'sweetviz', 'Pandasprofiling'.
We have built several models like 'Linear Regression', 'ARIMA model', 'Support Vector Machine(SVM) model','Long Short Term Memory(LSTM)','Random Forest model' and among all of these we have considered 'Random Forest' model for deployment as it has more accuracy.
And with 'Streamlit' we have deployed the model for predicting next 30 days values of stock price.
