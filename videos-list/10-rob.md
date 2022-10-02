```txt

Speaker: Rob Zinkov

Title: A Tour of Model Checking Techniques

Video: https://www.youtube.com/watch?v=vfqPGGCpY6I

Event description:
Have you ever written a model in PyMC and aren’t sure if it’s any good? In this talk I will show you the many ways you can evaluate how well your model fits your data using PyMC. Not all these techniques may be applicable for your particular problem, but you will definitely walk away with a few new tricks for being confident in the models you fit.

Discourse Discussion
https://discourse.pymc.io/t/a-tour-of-model-checking-techniques-by-rob-zinkov/6056

## Timestamps
00:00 Introduction
02:12 Model evaluation vs. model selection
05:31 Example: Predicting radon levels
07:13 Reading and cleaning the "Radon Contamination" dataset
07:55 Comparing complete pooling, no pooling, and partial pooling radon models
09:59 Predictive accuracy
11:05 Splitting in-sample and out-of-sample data and fitting against in-sample data for all 3 models
12:26 Calculating root mean square error (RMSE) and comparing scores
15:21 Cross validation
16:05 Likelihood on held-out data
16:35 "Frequentist" method: held-out likelihood using point estimates
18:34 "Bayesian" method: marginal likelihood using sample smc
19:40 Bayes factors
21:16 The drawbacks of using Bayes factors for choosing models
22:33 Prior and posterior predictive checks for model evaluation
23:02 Prior predictive checks
24:03 Posterior predictive checks
26:39 Information criterions
27:08 Akaike information criterion (AIC)
27:53 Bayesian information criterion (BIC)
28:43 Deviance information criterion (DIC)
30:25 Watanabe-Akaike or Widely-Available information criterion (WAIC)
32:19 Leave One Out Cross Validations (LOOCV)
33:39 Posterior dispersion indices
35:51 Two-sample tests
39:06 Relative maximum mean discrepancy (Relative MMD)
40:17 Kernel Stein Discrepancy (KSD)
42:20 Example: Predicting crime in Chicago
44:13 Summary: Flowchart for model evaluation
45:18 Summary: Flowchart for model selection
46:02 Closing remarks

Speaker bio:
Rob Zinkov is a PhD student at University of Oxford. His research covers how to more efficiently specify and train deep generative models as well as how to more effectively discover a good statistical model for your data. Previously, he was a research scientist at Indiana University where he was the lead developer of the Hakaru probabilistic programming language.

Speaker info:
-Twitter: https://twitter.com/zaxtax
-GitHub: https://github.com/zaxtax
-Website: https://zinkov.com/

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #PyMC #statistics
```
