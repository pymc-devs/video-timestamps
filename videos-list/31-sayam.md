```txt

Speaker: Sayam Kumar

Title:  Demystifying Variational Inference

Video: https://www.youtube.com/watch?v=IrudJ-dgfOw

Event description:
What will you do if MCMC is taking too long to sample? Also what if the dataset is huge? Is there any other cost-effective method for finding the posterior that can save us and potentially produce similar results? Well, you have come to the right place. In this talk, I will explain the intuition and maths behind Variational Inference, the algorithms capturing the amount of correlation, out of the box implementations that we can use, and ultimately diagnosing the model to fit our use case.

Discourse Discussion
https://discourse.pymc.io/t/demystifying-variational-inference-by-sayam-kumar/6022

## Timestamps
00:00 Start 
01:08 Agenda(Bayes Rules, Variational Inference, Approbations, Out of the box implementation, model diagnostics)
01:58 Bayes Formula 
03:07 Example of mean and standard deviation for normally distributed data 
04:58 Joint log probability 
06:50 Markov chain for drawing more sample 
07:12 Variational Inference 
07:45 Information and Kl divergence
08:48 Evidence lower Bound (ELBO)
09:35 ELBO maximization  
10:06 Monte Carlo approximation  
11:11 Warning! (What if the sample do not match support distribution)
12:05 Transformations
14:25 Who don't like vectorizing the code
15:04 Where we are
16:06 Mean Field ADVI
17:58 Optimizer 
20:04 ELBO graph 
20:39 What more can we do 
22:27 Modelling the correlation (Full rank ADVI and Low rank ADVI)
23:12 Out of the box implementations (TFP and PyMC3/4)
23:50 PyMC4 implementation 
25:26 MCMC vs VI
26:34 Hierarchical Modelling with PyMC4
27:08 Covariation intercept model 
28:26 Generating random correlation matrix in PyMC4
31:07 Graph of correlation 
33:21 Diagnosing the model fit 
34:39 Take aways (End of the talk)

Speaker bio:
Sayam Kumar is a Computer Science undergraduate student at IIIT Sri City, India. He loves to travel and study maths in his free time. He also finds Bayesian statistics super awesome. He was a Google Summer of Code student with NumFOCUS community and contributed towards adding Variational Inference methods to PyMC.

Speaker info: 
-Twitter: https://twitter.com/sayamkumar753 
-GitHub:  https://github.com/Sayam753
-LinkedIn: https://www.codingpaths.com/

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #statistics 
```
