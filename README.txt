Simulation study for Bayesian hierarchical model.

R package longTransients must be installed:

  install.packages("path/to/longTransients_1.1.tar.gz", repos = NULL)

simulate_trajectories.R creates the simulated data stored in /data

Scripts Figure 1.R, Figure 2.R, Figure 3.R and Figure 4.R create corresponding Figures 1-4 in the manuscript. 

kl_combinations.R fits the parametric model to subsets of the simulated trajectories used to create Figure 5.

kl_divergence.R summarizes the results of the fits in kl_combinations.R through numerical approximations of marginal KL divergences to create Figure 5.

neg_grad_potential_plot.R creates Figure 6.

The simulation_study.R script fits both models to several subsets of the 10 simulated trajectories for a single value of the measurement error variance. The script also creates Figure 7.

single_combinations.R fits both models to one subset of the simulated trajectories.

