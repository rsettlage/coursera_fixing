## Computational Statistics Outline



### Objective

The objective of this specialization is to introduce Statistical Computing or Computational Statistics to aspiring or new data scientists. The attendees will learn the basics of probability and bayesian inference. This will be followed by a series of lectures on how to perform inference approximately when exact calculations are not not viable. Finally, PyMC3 will be introduced along with its application to some real world scenarios.	

> Give some examples of MCMC inference so folks get a sense of what can be done including examples from Fintech. Why are we learning MCMC or Bayesian inference?



### Structure

For an overview of lessons and modules visit https://partner.coursera.help/hc/en-us/articles/203739139

1. 3 modules per course, each module should have a graded assessment of > 30min, 1 practice assessment of unspecified time

2. 3 courses

3. Each lesson should 

   1. take about 30 mins to complete and is a standalone concept
   2. can have 1 or two learning objectives
   3. end with an ungraded assessment

4. A module should 

   1. take 1 week to complete

   2. include 2 lessons at least

      

### Course Outline

1. **Introduction to Probability and Distributions** 

   | Time                       | Modules | Weeks | Duration         |
   | -------------------------- | ------- | ----- | ---------------- |
   | 8.5hrs + assessment (2hrs) | 3       | 3     | Jan 25 to Feb 25 |

   1. Probability (1hr).   
   2. Bayesian and Frequentist approach (0.5hr)
   3. Databricks Environment for notebooks - provisioning, installing packages, accessing data and Docker images (1hr)
   4. Sampling (2hrs)
   5. Types of Distributions (3hrs)
   6. Priors (1hr)




##### Total time of video lectures = 186 min video

##### Total time of graded content = 

##### Total time of ungraded content =



##### Module 1 (15 min video) - Maybe not a module - 1 day

- Intro to Course (3 min video)

- Intro to website (7 min video)
  - Binder, colab, local environment

- Intro to Databricks notebooks (5 mins)

##### Module 2 (75 min video, 12+ min graded, 10+ min ungraded )

- Probability (Robert) 
  - (10 x 6 min videos)

- Bayesian and Frequentist approach (3 x 5 min videos) 
  - **NEED TO ADD**  *3 ungraded (10mins)*
  -  *4 graded (12 mins)*

##### Module 3 (69 min video, 43 min graded, 62 min ungraded) 3 days

- Distributions 
   - Each distribution has a 5 min video - (9 x 5 min = 45 min videos)
      - *Each distribution has an ungraded evaluation by interacting with the visualization (30 mins)* 
      - *Graded evaluation (27 mins)*
   - Generate data and Parameter estimation (5 min video)
      - *Ungraded 20 mins*
   - Gaussian Mixture Models
      - Theory (5 min video)
      - Code and Information Criterion (7 min video)
      - **NEED TO ADD 2 questions** *for Ungraded 6mins*
      -  *Graded 15 mins*

- Non-parametric Methods and Kernel Density Estimation (7 min video)
  - *Ungraded 20 mins*
   -  *Graded 10 mins*

#####  Module 4 (27 min video, 22 min graded, 30 min ungraded) 1 day

- Introduction to Sampling (2 min video)
- Sampling from Discrete Distributions (7 min video)
  - **NEED TO ADD** *3 questions for graded (10mins)*
- Inverse Transform Method (7 min video)
  - *Ungraded evaluation 30 mins*
- Rejection Sampling Method (7 min video)
- Importance Sampling Method (4 min video)
  - **NEED TO ADD** *4 questions for graded 12 mins*



1. **Bayesian Inference with MCMC** 

   | Time                      | Modules | Weeks | Duration         |
   | ------------------------- | ------- | ----- | ---------------- |
   | 9.5hrs+ assessment (2hrs) | 3       | 3     | Feb 25 to Mar 25 |

   1. Bayesian Inference

      1. Underfitting vs. overfitting, simplicity vs. accuracy (0.5hr)  - *Bayesian Analysis with Python*
      2. Predictive accuracy measures including empirical strategies such as cross-validation and Information Criteria measures such as Log-likelihood, Akaike Information Criteria, Widely   Applicable Information Criteria, Bayesian Information Criteria ( 2hrs)- *Bayesian Analysis with Python*
      3. Entropy and KL Divergence (1hr) - *Bayesian Analysis with Python*
      4. Model Averaging (1hr) - *Bayesian Analysis with Python*
      5. Ergodicity - *Pattern Recognition Bishop Chapter 11*

   2. MCMC with Metropolis Algorithm (1.5hrs) - *VT Book*

   3. MCMC with Metropolis Hastings Algorithm (1.5hrs) - *VT Book*

   4. MCMC with Gibbs Sampling (1.5hrs) - *VT Book*

   5. Hamiltonian Monte Carlo (0.5hr) ? - *Pattern Recognition Bishop Chapter 11 Sampling methods, Video by Betancourt* 



##### Module 1 (56 min video, 30 min graded, 90 min ungraded) - 3 days

- Intro to Course (3 min video)
- R2 and Explained Variance (5 min video)
- Underfitting vs. Overfitting, Simplicity vs. Accuracy (5 min video)
- Cross Validation (5 min video)
- Log-likelihood and Deviance (5 min video)
- Posterior predictive
- AIC, BIC, DIC and WAIC (7 min video)
- A Qualitative discussion of the above metrics
- Entropy (7 min video)
  - *Ungraded evaluation (30 min)*
- KL Divergence (7 min video)
  - *Ungraded evaluation (1 hr)*
- Model Averaging (7 min video)
- Stationarity and Ergodicity (5 min video)
  - *Graded evaluation (30 min)*



##### Module 2 (49 min video, 30 min graded, 200 min ungraded) - 2 days

- Building blocks - Markov Chains (2 min video)
- Building blocks - Why does it work? (7 min video)
- Foundations of Bayesian Inference (5 min video)
- Outline of the Metropolis Algorithm (7 mins video)
- Details of the Metropolis Algorithm (7 mins video)
- Building the Inferred Distribution (7 mins video)
- Python Code for the Metropolis Algorithm (7 min video)
  - *Ungraded evaluation 50 min*

- Introduction to the Metropolis-Hastings Algorithm (7 min video)
  - *Ungraded evaluation 150 min*

- *Graded questions 10 for 30 mins* 



##### Module 3 (30 min video, 30 min graded, 120 min ungraded) 2 days

- Introduction to Gibbs Sampling (7 min)

- Details of the Gibbs Sampling algorithm 1 (4 min)

- Details of the Gibbs Sampling algorithm 2 (7 min)

  - *Ungraded Evaluation 120 mins*

- Hamiltonian Monte Carlo (7 min)

- Characteristics of MCMC (5 min)

- *Graded Evaluation 10 questions of 30 mins*

  



1. **Introduction to PyMC3 with applications** 

   | Time                       | Modules | Weeks | Duration         |
   | -------------------------- | ------- | ----- | ---------------- |
   | 8.5hrs + assessment (2hrs) | 3       | 3     | Mar 25 to Apr 25 |

   1. Introduction to PyMC3 for MCMC and ArViz for visualization (3hrs)
   2. Gaussian distribution fit to NMR example, example with Student’s-t distribution and posterior predictive checks (2hrs)
   3. Linear regression with MCMC using PyMC3, Hierarchical Linear Regression (2.5hrs)
   4. Case Study with PyMC3 (2 hr) - Bayesian Modeling of the Temporal Dynamics of COVID-19  



##### Module 1 (70 min video, 38 min graded) 3 days

- Intro to Course (2 min)
- Introduction to PyMC3 (5 min)
- Introduction to PyMC3 with Linear Regression (5 min)
- Introduction to PyMC3 - Traces (5 min)
- Composition of Distributions for Uncertainty (7 min)
  - *Graded questions of 2 for 5 min*
- Highest Posterior Density and Region of Practical Equivalence (7 min)
  - *Graded questions of 5 for 15 min*
- Credible Intervals and Confidence Intervals (5 min)

- Modeling with a Gaussian Distribution and Using PyMC3 to Model a Phenomenon with a Gaussian distribution (7 min)
- Posterior Predictive Checks (5 min)
- Robust Models with a Student's t-Distribution (7 min)
- Hierarchical/Multilevel Models (7 min)
- Hierarchical Models - Shrinkage (7 min)
-  *Graded questions 6 for 18 min*



##### Module 2 (67 min video) 3 days

- Linear Regression (5 min)
- Mean-center for Linear Regression (5 min)
- Robust Linear Regression
- Hierarchical Linear Regression - Part 1 (5 min)
- Polynomial Regression for Non-linear Data (7 min)
- Multiple Linear Regression (7 min)
- Logistic Regression intro 
- Logistic Regression example
- Visualizing the Decision Boundary
- Multiple Logistic Regression (7 min)
- Multiclass Classification (5 min)
- Inferring Rate Change with a Poisson Distribution - Part 1 (7 min)
- Inferring Rate Change with a Poisson Distribution - Part 2 (7 min)
- **NEED TO ADD** *10 graded questions for 30 min*



##### Module 3 (61 min video) 2 days

- Tuning (7 min)
- Metropolis
- Mixing and Potential Scale Reduction Factor (7 min)
- Centered vs. Non-centered Parameterization (7 min)
- Autocorrelation and Effective Sample Size (4 min)
- Monte Carlo Error (1 min) and divergence below together
- Divergence (7 min)
- Revisiting the Multiclass Classification problem (4 min)
- PyMC3 metrics - Part 1 (7 min)
- PyMC3 metrics - Part 2 (7 min)
- Diagnosing and Debugging MCMC with PyMC3 (7 min)
- ArViz Data Representation (3 min)
- **NEED TO ADD** 10 graded questions for 30 min
- PyMC3 COVID project (15 min video) 2 hrs ungraded evaluation 

### Per Course

* 1 introduction to course video - introduce the target audience, course prerequisites,  learning objectives 

* 3 modules
  * 1 hour of video per module, 3 hours of video per course, 7 minute maximum per video
  * Each module should have a module description

* 3 graded assessments, 1 per module,
  * 30 mins per graded assessment
  * Feedback at the end of each assessment

* 3 learning objectives, each objective aligns with an assessment

* 3 practice assessments, 1 per module



Why Inferential Statistics over Descriptive Statistics?

### Coursera notes

![Screen Shot 2020-08-20 at 5.48.28 AM](Coursera1.png)



![Screen Shot 2020-08-20 at 5.48.28 AM](Coursera2.png)

![Screen Shot 2020-08-20 at 5.49.15 AM](Coursera3.png)

