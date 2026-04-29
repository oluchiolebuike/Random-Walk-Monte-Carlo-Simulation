# Random-Walk-Monte-Carlo-Simulation

This experiment uses a Monte Carlo simulation to estimate the probability that a person remains within a Manhattan distance of 4 blocks from the origin after a random walk of varying lengths. For each walk length from 1 to 30, 20 000 random walks are simulated, where each step is equally likely to move north, south, east or west. 

The final position of each walk is used to compute the Manhattan distance, given by ∣x∣+∣y∣ and the proportion of walks that end within a distance of 4 is recorded as an estimate of the probability.

The results show a clear decreasing trend: as the number of steps increases, the probability of remaining close to the starting point declines. This is because longer walks allow for greater dispersion from the origin. The simulation also exhibits slight fluctuations due to randomness and the discrete grid structure, but overall it demonstrates how probabilistic behaviour can be approximated through repeated sampling.
