# Efficient-Frontier-Python

The Efficient Frontier is a concept in Modern Portfolio Theory that represents a set of portfolios that offer the highest expected return for a given level of risk or the lowest risk for a given level of expected return. The Efficient Frontier is constructed by plotting the expected returns of different portfolios against their respective standard deviations of returns.

To construct the Efficient Frontier, we can use the Markowitz model, which is a mathematical model that uses optimization techniques to find the optimal portfolio for a given level of risk. The Markowitz model considers the expected returns of different assets, their standard deviations, and their correlations to find the optimal weights to allocate among the assets.

To estimate the expected returns, standard deviations, and correlations of the assets, we can use historical data. However, historical data might not always be a reliable predictor of future returns, so we can also use Monte Carlo simulation to generate a range of possible outcomes for the assets.

Here's an outline of how we can use Python to implement the Efficient Frontier using Markowitz and Monte Carlo simulation:

Collect historical data for the assets of interest. We can use the pandas




