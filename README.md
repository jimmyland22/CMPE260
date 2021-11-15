# CMPE-260 Term Project: Stock Market Predictor Using Temporal Difference

## Team
* Jimmy Liang
* Rohan Kumar
* Samer Baslan

## Summary 
The stock market prediction problem is considered to be a Markov process which can be optimized by using reinforcement learning based algorithms. Temporal difference, a reinforcement learning algorithm which leams only from experiences, will be adopted and function approximation by artificial neural network will be performed to leam the values of states each of which corresponds to a stock price trend at a given time.

## Prerequisite
* Hardware accelerator: TPU (peferred)

## Results
Amazon (AMZN) was chosen for its mixture of long-term growth with frequent fluctuation. It was observed around the 700th (out of 1000) episode that the agent met or outperformed the market moving average.

![AMZN](https://github.com/jimmyland22/CMPE260/blob/main/results/AMZN_performance.png)

## References
* https://www.baeldung.com/cs/epsilon-greedy-q-learning
* https://exchange.ml4trading.io/