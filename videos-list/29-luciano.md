```txt

Speaker: Luciano Paz

Title: Posterior Predictive Sampling in PyMC

Video: https://www.youtube.com/watch?v=IhTfuO8wSDA

Event description:
PyMC is great for inferring parameter values in a model given some observations, but sometimes we also want to generate random samples from the model as predictions given what we already inferred from the observed data. This kind of sampling is called posterior predictive sampling, and it can be very hard. The typical problems that show up are related to shape mismatches in hierarchical models, latent categorical values that aren’t correctly re-sampled or changing the shape of the data between the training and test phases. In this presentation I’ll talk about how posterior predictive sampling is implemented in PyMC, show some typical situations where it fails, and how to make it work.

Discourse Discussion
https://discourse.pymc.io/t/posterior-predictive-sampling-in-pymc3-by-luciano-paz/6028

## Timestamps
- 0:00 Start of event
- 0:22 Background on PyMC3 common workflow and posterior predictive distribution
- 2:56 What is this presentation about?
- 3:19 Simple model without posterior predictive problems
- 4:27 Create train and test data
- 5:12 Translate the math into PyMC3
- 6:52 Visualize and plot the model and predictions
- 8:20 Make predictions on the new data
- 9:29 Shape problems 
- 12:46 A simple extension of linear regression
- 17:26 View the results of the extension
- 17:50 Error on the test data
- 19:15 What happens if we try to marginalize label out of the model?
- 21:38 Shape problem with the test data
- 22:55 Solution, a functional approach 
- 27:50 Factory functions aren’t a silver bullet
- 28:12 Manually trim the inferred posterior
- 29:22 Challenges with sampling 
- 32:10 How can PyMC help?
- 32:45 Conclusion

## Note: help us add timestamps here
https://github.com/pymc-devs/video-timestamps

Speaker bio:
Luciano got into Bayesian stats during his PhD in cognitive neuroscience. During his postdoc he got more involved with machine learning, and discovered PyMC. He became a core contributor of PyMC, learnt a lot in the process and made up his mind to pursue a career outside of academia. He is now a machine learning engineer at Innova SpA in Italy.

Speaker info: 
-GitHub:  https://github.com/lucianopaz
-Website: https://lucianopaz.github.io/
-LinkedIn: https://it.linkedin.com/in/luciano-paz-4139b5123

Part of PyMCon2020. 
More details at http://www.pymcon.com  

#bayesian #PyMC #sampling
```
