# A3C-Stock-broker
This is a (failed) project that attempted to come up with a winning strategy for trading forex pairs. I believe it failed due to a lack of information and lack of data normalization. I would like to revisit this some time in the future, after learning more about current methods of stock forecasting.

The basic way it worked was this:
1) I scraped the last ten years of Forex data off of a website
2) I visualized the data to decide what is the best interval of time to try to make a prediction. I  didn't include my visualizations in this repo.
3) I transformed the data into the ohlc every ten minutes, then tried to predict it with a rnn regressor
4) this fed into a reinforcement algorithm
