# Inference in Probabilistic Models - Sampling Methods

Michael Habeck - Jena University Hospital - michael.habeck@uni-jena.de

Wolfhart Feldmeier - Jena University Hospital - wolfhart.feldmeier@uni-jena.de

## Dates and course organization

* Four weeks, two 2-hour lectures plus one 2-hour exercise session per week

* Lectures on Monday and Friday, exercises on Wednesday

* Timetable

| Lecture   | Date         | Weekday | Time          | Topic                                  | 
|:---------:|:------------:|:-------:|---------------|:---------------------------------------|
| 1         | Jan 15, 2024 | Mon     | 10:15 - 11:45 | Introduction / Direct Sampling Methods |
| Ex 1      | Jan 17, 2024 | Wed     | 10:15 - 11:45 | Exercises for lecture 1                |
| 2         | Jan 19, 2024 | Fri     | 10:15 - 11:45 | Rejection & Importance Sampling        |
| 3         | Jan 22, 2024 | Mon     | 10:15 - 11:45 | Markov chains, MCMC                    |
| Ex 2      | Jan 24, 2024 | Wed     | 10:15 - 11:45 | Exercises for lectures 2-3             |
| 4         | Jan 26, 2024 | Fri     | 10:15 - 11:45 | The Metropolis-Hastings algorithm      |
| 5         | Jan 19, 2024 | Mon     | 10:15 - 11:45 | Gibbs sampling                         |
| Ex 3      | Jan 31, 2024 | Wed     | 10:15 - 11:45 | Exercises for lectures 4-5             |
| 6         | Feb 02, 2024 | Fri     | 10:15 - 11:45 | Hamiltonian Monte Carlo                |
| 7         | Feb 05, 2024 | Mon     | 10:15 - 11:45 | Hamiltonian Monte Calro II             |
| Ex 4      | Feb 07, 2024 | Wed     | 10:15 - 11:45 | Exercises for lectures 6-7             |
| 8         | Feb 09, 2024 | Fri     | 10:15 - 11:45 | Practical aspects of HMC               |

## Topics

### Lecture 1: Introduction & Direct Sampling Methods

* Motivation
* Monte Carlo approximation
* An inefficient way of computing $\pi$
* Can we beat the curse of dimensionality?
* Random number generation
* Direct sampling by variable transformation methods

### Lecture 2: Rejection and Importance Sampling

* More direct sampling methods
* Rejection sampling
* Importance sampling

### Lecture 3: Markov chains

* Markov chains
* Some mathematical facts about Markov chains

### Lecture 4: The Metropolis-Hastings Algorithm

* Fundamental theorem of Markov chains
* Metropolis-Hastings algorithm

### Lecture 5: Gibbs sampling

* Combining Markov chains
* Gibbs sampling

### Lecture 6: Hamiltonian Monte Carlo

* Auxiliary variable methods
* Hamiltonian Monte Carlo I

### Lecture 7: Hamiltonian Monte Carlo

* Hamiltonian Monte Carlo II

### Lecture 8: Hamiltonian Monte Carlo, Practical Issues

* Practical Issues (convergence, diagnostic checks)


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