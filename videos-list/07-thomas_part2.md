```txt

Speaker: Thomas Wiecki

Title:  The Bayesian Workflow: Building a COVID-19 Model (Part 2)

Video: https://www.youtube.com/watch?v=_DCkJkMji0U

Event description: 
In this tutorial we will build a COVID-19 model from scratch.

Discourse Discussion
https://discourse.pymc.io/t/the-bayesian-workflow-building-a-covid-19-model-by-thomas-wiecki/6017

## Timestamps

00:00 Intro - Motivation for Generative Models in Bayesian Statistics
00:50 Agenda 
01:08 Adressing Limitations of previous model using Rt
01:31 Current Rt model in use from rt.live
02:38 Delay effects on Rt we should take into account 
03:06 Effects of Tracking lockdowns, mask use and social distancing on Rt

03:45 The generative model 
04:21 Dataset - US new daily cases 
04:42 Build a generative model using a recursive function for new cases
06:03 Mapp the recursive loop into pymc3 object with theano.scan
07:06 Instantiate model and set parameters 
10:33 Follow the bayesian workflow 
11:25 Time varying reproduction

12:28 Select prior with time-varying factor(random walk process)
14:41 Update model with new prior
16:00 Prior and Posterior predictive results 

17:23 Taking infection delay into account - generation time distribution
18:00 Modeling of generation time distribution of covid 19 
19:03 Convolution definition
20:38 Updating generative process model with a convolution
21:50 Prior and Posterior predictive results  
23:18 Compare models 

23:49 The number of infected - onset delay distribution
24:50 Update model with onset delay effect
26:26 Prior and Posterior predictive results 

27:28 Adjusting for number of tests performed 
29:35 Results discussion
30:05 Conclusion/Final remarks


Speaker bio:

- Thomas is the founder of PyMC Labs, a Bayesian consulting firm.
- PyMC author
- PhD on computational cognitive neuroscience from Brown University
- Former VP of data science and head of research at Quantopian Inc: building a team of data scientists to build a hedge fund from a pool of 300k crowd researchers.
- Recognized public speaker: keynotes at the Open Data Science Conference (ODSC) & TACC as well as talks at Strata Hadoop & AI, Newsweek AI conference, and various PyData conferences around the world
- Runs a data science podcast, blogs about Bayesian statistics, and is an avid Twitter personality.
- Data scientist to follow of the year 2015, ODSC Open Source award 2018.

Speaker info: 
-Website: https://twiecki.io
-GitHub: https://github.com/twiecki
-Twitter: https://twitter.com/twiecki
-LinkedIn: https://www.linkedin.com/in/thomas-wiecki-46339244/  

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #statistics #covid19
```
