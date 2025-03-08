# mpnn

Markov process neural networks.

This project was done for the Random Processes course at Tsinghua Shenzhen International Graduate School. In this project, I work with a Markov process neural network, where the parameters of the neural network follow a Gauss-Markov process. Sequential Monte Carlo is used to "learn" from data generated one point at a time from a moving function. With this method, the neural network does not have to be differentiable, but it does not scale well to high dimensions, so it can only be used with very small neural networks. Julia code is provided in a Pluto notebook, but it is currently not very well documented. I will update it later when I have time.

Animated visualizations of the predictions are shown below. The upper plot shows the empirical cumulative distribution function of y (conditional on x), while the lower plot shows the median and the 95% mid-quantile interval of y, i.e. the interval between the 2.5% quantile and the 97.5% quantile (conditional on x).

![Prediction visualization](img/pred.gif)
