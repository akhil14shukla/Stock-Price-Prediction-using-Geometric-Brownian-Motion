Stock Price Prediction

Disclaimer:
Do not use our model directly to buy or sell stocks in real life, we do not guarantee any success.

We will use Geometric Brownian Motion to predict the sotck price.
![Akhil and Shivam Collaborations](stonks.jpg)
On the stock exchange, the stock is the most traded instrument. They are a source of income to the companies and investors, but they are intertwined with risk. Thus predicting stock prices and that too with accuracy becomes very important. It can help to anticipate losses and thus provide optimal benefit to the investors.
In this project report, we start with the aim of predicting Stock prices using Geometric Brownian Motion(GBM). First, we establish the concept of random walk and, using this, define Brownian Motion. Then, we see Itô’s Process and Itô’s Lemma, which are used to find the differential of time-dependent Stochastic Process. After we have laid these groundworks, we obtain the expression for GBM, using Itô’s Lemma, and state the correspondence with Brownian Motion with Drift. But the expression for GBM contains parameters, so using the historical data, we calculate these parameters. Then we see how these parameters can be estimated. We write the code of our GBM model and parameter estimation in Python, predict the stock prices and compare our result with the actual stock prices.


