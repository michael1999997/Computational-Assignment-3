# Computational-Assignment-3
This repository addresses the following tasks:

Data Generation (3-Parameter Logistic Model):

Generate synthetic binary data using a logistic regression model with known parameters.
Analyze the number of 0’s and 1’s in the data.
Random-Walk Metropolis-Hastings (3 Parameters):

Sample from the posterior distribution using a spherical Gaussian proposal.
Tune the proposal scaling to achieve a 23.4% acceptance rate.
Visualize convergence using:
Trace Plots
Histograms
Gelman-Rubin statistic (
𝑅
^
R
^
 ) for 20 independent chains.
Extension to a 9-Parameter Logistic Model:

Increase the dimensionality of the logistic model to 9 parameters.
Tune the proposal scaling to maintain the 23.4% acceptance rate.
Perform the same convergence diagnostics as in Task 2.
Metropolis-within-Gibbs (MWG):

Use MWG to cycle through the conditionals for the 9 parameters.
Tune each conditional proposal to achieve a 15% acceptance rate.
Assess convergence using 
𝑅
^
R
^
  for 10 independent chains.
Mixed-Proposal Strategy:

Propose updates with:
50% probability: Low proposal scale (target ~10% acceptance rate).
50% probability: High proposal scale (target ~30% acceptance rate).
Evaluate whether this mixed-proposal strategy achieves faster convergence.
Use the 
𝑅
^
R
^
  statistic to measure convergence for 20 independent chains.
