# basketball_variance
Does the recent trend in the NBA where more three-pointers are attempted per game result in greater average score and more variability in a team's total score over a season? (Yes)

We can model the number of successful shots (made baskets) in a given game using the binomial distribution. Assume that each shot attempt is independent of each other (no hot hand) and that the number of attempts per game is constant (games with more threes probably have more total possessions). Given 100 possessions per game and a probability of making a three of 0.35, a game where only three pointers are attempted will have a standard deviation of sqrt(100\*0.35\*(1-0.35))\*3 = 14.31

On the other hand, a game where only two pointers are attempted with a probability of success of 0.5 will have a standard deviation of sqrt(100\*0.5\*(1-0.5))\*2 = 10. The simulation in the IPython notebook confirms these results.
