# Inference in Probabilistic Models - Sampling Methods

Michael Habeck - Jena University Hospital - michael.habeck@uni-jena.de

Wolfhart Feldmeier - Jena University Hospital - wolfhart.feldmeier@uni-jena.de

## Dates and course organization

* Six weeks, two 2-hour lectures plus one 2-hour exercises session per week

* Lectures on Monday and Friday, exercises on Wednesday

* Timetable

| Lecture   | Date         | Weekday | Time          | Topic                             | 
|:---------:|:------------:|:-------:|---------------|:----------------------------------|
| 1         | Dec 16, 2022 | Fri     | 10:15 - 11:45 | Introduction                      |
| 2         | Jan 02, 2023 | Mon     | 10:15 - 11:45 | Direct Sampling Methods           |
| Ex 1      | Jan 04, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 1-2        |
| 3         | Jan 06, 2023 | Fri     | 10:15 - 11:45 | Rejection & Importance Sampling   |
| 4         | Jan 09, 2023 | Mon     | 10:15 - 11:45 | Markov chains, MCMC               |
| Ex 2      | Jan 11, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 3-4        |
| 5         | Jan 13, 2023 | Fri     | 10:15 - 11:45 | The Metropolis-Hastings algorithm |
| 6         | Jan 16, 2023 | Mon     | 10:15 - 11:45 | Gibbs sampling                    |
| Ex 3      | Jan 18, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 5-6        |
| 7         | Jan 20, 2023 | Fri     | 10:15 - 11:45 | Hamiltonian Monte Carlo           |
| 8         | Jan 23, 2023 | Mon     | 10:15 - 11:45 | Practical aspects of HMC          |
| Ex 4      | Jan 25, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 7-8        |
| 9         | Jan 27, 2023 | Fri     | 10:15 - 11:45 | Slice sampling                    |
| 10        | Jan 30, 2023 | Mon     | 10:15 - 11:45 | Practical aspects, Diagnostics    |
| Ex 5      | Feb 01, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 9-10       |
| 11        | Feb 03, 2023 | Fri     | 10:15 - 11:45 | TBA                               |
| 12        | Feb 06, 2023 | Mon     | 10:15 - 11:45 | TBA                               |
| Ex 6      | Feb 08, 2023 | Wed     | 10:15 - 11:45 | Exercises for lectures 11-12      |
| 13        | Feb 10, 2023 | Fri     | 10:15 - 11:45 | TBA                               |

## Topics

### Lecture 1: Introduction

* Motivation
* Monte Carlo approximation
* An inefficient way of computing $\pi$

### Lecture 2: Direct Sampling Methods

* Can we beat the curse of dimensionality?
* Random number generation
* Direct sampling by variable transformation methods

### Lecture 3: Rejection and Importance Sampling

* More direct sampling methods
* Rejection sampling
* Importance sampling

### Lecture 4: Markov chains

* Markov chains
* Some mathematical facts about Markov chains

### Lecture 5: The Metropolis-Hastings Algorithm

* Fundamental theorem of Markov chains
* Metropolis-Hastings algorithm

### Lecture 6: Gibbs sampling

* Recap: Metropolis-Hastings algorithm
* Combining Markov chains
* Gibbs sampling
* Auxiliary variable methods

### Lecture 7: Hamiltonian Monte Carlo

* Recap: MCMC + Gibbs Sampling
* More on auxiliary variable methods
* Hamiltonian Monte Carlo

### Lecture 8: Hamiltonian Monte Carlo, Practical Issues

* Hamiltonian Monte Carlo continued
* Practical Issues (convergence, diagnostic checks)

### Lecture 9: Slice sampling

* General slice sampling
* Neal's bracketing method

#### Lecture 10:  Practical Aspects of MCMC

* Convergence, diagnostic checks

### Lectures 11-13: TBA

#### Possible topics

* Annealed Importance Sampling
* Nested Sampling
* Parallel Tempering / Replica-exchange Monte Carlo
* Sequential Monte Carlo (SMC)
* Graphical models
* Ising model
* Simulator models
* Stochastic differential equation & Langevin dynamics
* Bridge sampling, thermodynamic integration
* Partition function estimation
* Intractable models
* Exchange algorithm
* Adaptive Monte Carlo methods
* Wang-Landau
* Exact sampling: coupling from the past

# Literature

* Matti Vihola: [Lectures on Stochastic Simulation](http://users.jyu.fi/~mvihola/stochsim/notes-2020.pdf)

* Radford Neal: [Probabilistic Inference Using Markov Chain Monte Carlo Methods](https://www.cs.toronto.edu/~radford/ftp/review.pdf)

* Chris Bishop: [Pattern Recognition and Machine Learning, Chap. 11](https://www.springer.com/gp/book/9780387310732)

* David MacKay: [Information Theory, Inference, and Learning Algorithms, Chap. 29 + 30](http://www.inference.org.uk/itprnn/book.pdf)

* Iain Murray: [Advances in Markov chain Monte Carlo methods](http://homepages.inf.ed.ac.uk/imurray2/pub/07thesis/murray_thesis_2007.pdf)

* Andrieu, de Freitas, Doucet, Jordan: [An Introduction to MCMC for Machine Learning](https://link.springer.com/article/10.1023/A:1020281327116)

* Charles Geyer: [Introduction to Markov Chain Monte Carlo](http://si.biostat.washington.edu/sites/default/files/modules/Geyer-Introduction%20to%20markov%20chain%20Monte%20Carlo_0.pdf)

* Jun S. Liu: [Monte Carlo Strategies in Scientific Computing](https://www.springer.com/de/book/9780387763699)

* David A Levin, Yuval Peres: [Markov chains and mixing times](https://www.academia.edu/download/30694248/recent.pdf)