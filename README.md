# Probabilistic Inference

This repository contains lecture materials for the Probabilistic Inference lecture (currently WS 22/23) at Uni Jena.

## Structure

The repository contains ten lectures in total, distributed into two (+1) notebooks:

* [00-Overview.ipynb](00-Overview.ipynb)

* [01-Sampling.ipynb](01-Sampling.ipynb)
    * Lecture 1: Introduction
        * Motivation
        * Monte Carlo approximation
        * An inefficient way of computing $\pi$

    * Lecture 2: Direct Sampling Methods
        * Can we beat the curse of dimensionality?
        * Random number generation
        * Direct sampling by variable transformation methods

    * 3: Rejection and Importance Sampling
        * More direct sampling methods
        * Rejection sampling
        * Importance sampling

* [02-MCMC.ipynb](02-MCMC.ipynb)
    * Lecture 4: Markov chains
        * Markov chains
        * Some mathematical facts about Markov chains

    * Lecture 5: The Metropolis-Hastings Algorithm
        * Fundamental theorem of Markov chains
        * Metropolis-Hastings algorithm

    * Lecture 6: Gibbs sampling
        * Recap: Metropolis-Hastings algorithm
        * Combining Markov chains
        * Gibbs sampling
        * Auxiliary variable methods

    * Lecture 7: Hamiltonian Monte Carlo
        * Recap: MCMC + Gibbs Sampling
        * More on auxiliary variable methods
        * Hamiltonian Monte Carlo

    * Lecture 8: Hamiltonian Monte Carlo, Practical Issues
        * Hamiltonian Monte Carlo continued
        * Practical Issues (convergence, diagnostic checks)