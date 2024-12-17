# Computational-Assignment-3
This repository addresses the following tasks:
1.	Data Generation (3-Parameter Logistic Model):
o	Generate synthetic binary data using a logistic regression model with known parameters.
o	Analyze the number of 0’s and 1’s in the data.
2.	Random-Walk Metropolis-Hastings (3 Parameters):
o	Sample from the posterior distribution using a spherical Gaussian proposal.
o	Tune the proposal scaling to achieve a 23.4% acceptance rate.
o	Visualize convergence using:
	Trace Plots
	Histograms
	Gelman-Rubin statistic (R^) for 20 independent chains.
3.	Extension to a 9-Parameter Logistic Model:
o	Increase the dimensionality of the logistic model to 9 parameters.
o	Tune the proposal scaling to maintain the 23.4% acceptance rate.
o	Perform the same convergence diagnostics as in Task 2.
4.	Metropolis-within-Gibbs (MWG):
o	Use MWG to cycle through the conditionals for the 9 parameters.
o	Tune each conditional proposal to achieve a 15% acceptance rate.
o	Assess convergence using R^ for 10 independent chains.
5.	Mixed-Proposal Strategy:
o	Propose updates with:
	50% probability: Low proposal scale (target ~10% acceptance rate).
	50% probability: High proposal scale (target ~30% acceptance rate).
o	Evaluate whether this mixed-proposal strategy achieves faster convergence.
o	Use the R^ statistic to measure convergence for 20 independent chains.

