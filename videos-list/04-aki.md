```txt

Speaker: Aki Vehtari

Title:  [Keynote] These are a few of my favorite inference diagnostics

Video: https://www.youtube.com/watch?v=HKPm6txxxQM

Event description:
I discuss some old and some more recent inference diagnostics methods for Markov chain Monte Carlo, importance sampling, and variational inference. When the convergence fails, I simply remember my favorite inference diagnostics, and then I don’t feel so bad.

Discourse Discussion
https://discourse.pymc.io/t/keynote-these-are-a-few-of-my-favorite-inference-diagnostics-by-aki-vehtari/6180

## Timestamps
00:00 Introduction by Aki
00:22 Outline of the talk
00:48 Run inference many times
01:27 MCMC warm-up and convergence diagnostics
03:10 It is good to run several chains
03:49 Trace plots & convergence
04:24 Convergence in worm plots
04:53 Converge vs not converge
05:10 R-hat for MCMC convergence diagnostics
06:36 R-hat compares within and total variances - 50 warmup, 50 post warmup iterations
08:34 Running more - 500 warmup, 500 post warmup iterations
09:06 5000 warmup, 5000 post warmup iterations
09:50 Total variance and within chain variance
10:47 Overview versions of R-hat
12:42 R-hat versions 1-4
14:13 R-hat v1-v4 vs v5
15:10 R-hat v5: Rank normalization and folding
18:14 Effective sample size and Monte Carlo error
21:55 Local effective sample size (ESS)
24:43 Bulk-ESS and Tail-ESS
26:50 Rank plots
27:52 Traces vs. Rank plots
28:22 Uniformity check?
29:41 ECDF and ECDF difference
32:20 ECDF difference envelope for multiple chains
32:42 R* multivariate diagnostic
34:45 MCMC convergence and accuracy diagnostics
35:08 Variational inference (VI) convergence diagnostics
37:31 Convergence diagnostic for VI optimization
41:24 Split-R-hat
42:59 VI accuracy diagnostics
43:46 Importance sampling (IS)
45:24 Importance function
47:08 Example: normal approximation at the mode
51:13 Effective sample size for importance sampling
53:16 Pareto smoothed importance sampling
54:08 ESS and MCSE for importance sampling
54:39 Pareto k-hat diagnostic for VI
55:36 VI convergence and accuracy diagnostics
56:04 Stacking for non-mixing Bayesian computations
57:48 Favorite inference diagnostics
58:28 References
58:38 Software references

Speaker bio:
Aki is an Associate professor in computational probabilistic modeling at Aalto University, Finland.
His numerous research interests are Bayesian probability theory and methodology, especially probabilistic programming, inference methods, model assessment and selection, non-parametric models such as Gaussian processes, dynamic models, and hierarchical models.
Aki is also a co-author of the popular and awarded book « Bayesian Data Analysis », Third Edition, and the brand new « Regression and other stories ». He is also a core-developer of the seminal probabilistic programming framework Stan. An enthusiast of open-source software, Aki has been involved in many free software projects such as GPstuff for Gaussian processes and ELFI for likelihood inference.

Speaker info:
-Twitter: https://twitter.com/avehtari
-GitHub: https://github.com/avehtari
-Website: https://users.aalto.fi/~ave/

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #statistics #probabilistic
```
