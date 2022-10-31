```txt

Speaker: Tim Dodwell, Mikkel Lykkegaard and Grigorios Mingas

Title: The MLDA multilevel sampler in PyMC

Video: https://www.youtube.com/watch?v=NvsGyvAElLY

Event description: 
This presentation will give you the chance to know more about PyMC’s new multilevel MCMC sampler, MLDA, and help you use it in practice. MLDA exploits multilevel model hierarchies to improve sampling efficiency compared to standard methods, especially when working with high-dimensional problems where gradients are not available. We will present a step-by-step guide on how to use MLDA within PyMC3, go through its various features and also present some advanced use cases, e.g. employing multilevel PDE-based models written in FEniCS and using adaptive error correction to correct model bias between different levels.

Discourse Discussion
https://discourse.pymc.io/t/the-mlda-multilevel-sampler-in-pymc3-by-tim-dodwell-mikkel-lykkegaard-and-grigorios-mingas/5982

## Timestamps
00:00 Introduction
00:36 A three way plan of attack!
03:21 Bayesian Uncertainty Quantification - Vanilla MCMC Starts with Bayes' Theorem
06:13 Delayed Acceptance - Christen & Fox, 2005
07:39 Multilevel Delayed Acceptance - Adpt 1 - Finite Subchains
08:33 Multilevel Delayed Acceptance - Adpt 2 - Apply Recursively
09:50 MLDA in PyMC3
22:21 Correcting Coarse Models
23:40 Coarse Model Bias
25:01 Modelling the Bias
26:41 Adaptive Error Model
27:53 Example
38:43 What we would like from you - Contacts

https://github.com/pymc-devs/video-timestamps

Speaker bio:
Prof. Tim Dodwell has a personal chair in Computational Mechanics at the University of Exeter, is the Romberg Visiting at Heidelberg in Scientific Computing and holds a 5 year Turing AI Fellowship at the Alan Turing Institute where he is also an academic lead.

-Twitter: https://twitter.com/proftimdodwell
-Website: https://www.datacentricengineering.co.uk/team.html

Mikkel Lykkegaard is a PhD student with the Data Centric Engineering Group and Centre for Water Systems (CWS) at University of Exeter. His research is mainly concerned with Uncertainty Quantification (UQ) for computationally intensive forward models.

-Website: http://emps.exeter.ac.uk/engineering/staff/ml624
-LinkedIn: https://uk.linkedin.com/in/mikkelbue
 
Dr. Grigorios Mingas is a Senior Research Data Scientist at The Alan Turing Institute. He received his PhD from Imperial College London, where he co-designed MCMC algorithms and hardware to accelerate Bayesian inference. He has experience in a wide range of projects as a data scientist.

-GitHub: https://github.com/gmingas
-LinkedIn: https://uk.linkedin.com/in/gmingas

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #PyMC #statistics
```
