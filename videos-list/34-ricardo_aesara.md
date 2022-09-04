```txt

Speaker: Ricardo Vieira

Title:  PyMC, Aesara and Aeppl: The New Kids on The Block

Video: https://youtu.be/_APNiXTfYJw

## Resources
- Meetup event: https://www.meetup.com/pymc-online-meetup/events/286748916/
- Notebook: https://tinyurl.com/pymc-aesara-aeppl
- https://gist.github.com/ricardoV94/441d16ab2f31c4e173a3a143e77fb888

- PyMC V4 Release announcement: https://www.pymc.io/blog/v4_announcement.html
- PyMC V4 Release notes: https://github.com/pymc-devs/pymc/blob/main/RELEASE-NOTES.md
- PyMC website: https://www.pymc.io/welcome.html
- About Aesara: https://aesara.readthedocs.io/en/latest/index.html
- About Aeppl: https://aeppl.readthedocs.io/en/latest/

## Outline
- Introduction
- Aesara and random variables
- Aeppl and probabilities
- PyMC and the modern Bayesian workflow
- Q&A
- 
## Timestamps
00:00 Thomas Wiecki does introduction and background
08:38 1.0 Intro: PyMC, Aesara and AePPL: The New Kids on The Block
10:07 2.0 About Aesara
12:04 2.1 Crash course on: Numpy-like tensor operations
15:20 2.2 Compilation to different backends: Numba, JAX 
15:52 2.3 Automatic differentiation
16:55 2.4 Automatic computational stabilization and specialization
18:35 2.5 User friendly graph manipulation
20:12 2.6 Random variables (scalar, constant, shared variables in Aesara, create a normal random variable using Aesara, random number generator)
24:05 PyMC has a utility to create an Aesara function that updates seeds automatically
24:40 Q: no questions so far 
25:28 3.0 PyMC (random side); How PyMC uses Aesara functionality to do two of the most important operations in the Bayesian workflow, which are: doing prior predictive draws from a model & taking posterior predictive draws from the same model
25:48 3.1 Distributions in PyMC are just functions which return random variables
26:52 Handy way to debug models; helper function: pm.draw(x, draws=2)
27:35 3.2 A PyMC model is just an Aesara graph composed of multiple RandomVariables
29:05 3.3 Do prior predictive modeling with PyMC models
30:32 3.4 Do posterior predictive modeling with PyMC models
32:03 Q: no questions
32:35 4.0 AePPL: a new library in ecosystem of PyMC and Aesara, “Ae” is the prefix used; AePPL = Aesara Probabilistic Programming Language; Goal: convert Aesara graphs made of random variables into log probability graphs
34:00 4.1 Crash course in AePPL: Convert RandomVariable graphs into log-probability graphs
37:00 4.2 Create log-probability graphs conditioned on (arbitrary) operations
44:30 Q: Is there a PyMC example using a Gaussian random model with a unique distribution argument?
44:55 Q: Did I read somewhere that PyMC can now automatically exploit conjugacy during sampling? (AeMCMC)
45:38 5.0 PyMC: probability side
46:14 5.1 PyMC uses AePPLl to transform RandomVariable graphs into log-probability graphs
49:24 5.2 Sampling (or optimizing). Once you have the densities and gradients, you can start doing Bayesian inference. pm.find_MAP()
50:45 5.3 PyMC uses AePPL to build new distribution types (censoring process) (pm.Censored)
54:10 5.4 Users will be able to define arbitrary distributions (WIP)
58:50 Q: Which composition estimator does AePPL not yet support?
01:00:05 Q: What is the relationship between AePPL and Aesara
01:02:10 Q: How difficult would it be to support other data types?




## Event Description
In this talk, Ricardo Vieira will explore the inner workings of the newly released version of PyMC (v 4.0). He will take a cursory look at the Aesara backend, focusing on the brand new RandomVariable operators, which are the foundation of PyMC models. He will then talk about a self-contained PPL project (Aeppl) dedicated to converting Aesara RandomVariable graphs to probability functions. Finally, he will clarify how PyMC makes use of these two packages to create efficient random generator functions and probability evaluation functions, with the ultimate goal of facilitating a fully-fledged modern Bayesian workflow.

PyMC is a probabilistic programming library for Python that allows users to build Bayesian models with a simple Python API and fit them using Markov chain Monte Carlo (MCMC) methods.

Aesara is a Python library that allows users to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently. Aesara is based on Theano (https://github.com/Theano/Theano), which has been powering large-scale computationally intensive scientific investigations since 2007.

Aeppl is a new library focused on converting (arbitrary) graphs containing Aesara RandomVariables into joint log-probability graphs. It can understand complex graphs that include nested operations, conditionals, loops, and advanced indexing, allowing one to generate rich probability functions automatically without having to muddle through the mathematical details.

Speaker bio:
Ricardo Vieira is a PyMC developer and data scientist at PyMC Labs. He spent several years teaching himself Statistics and Computer Science at the expense of his official degrees in Psychology and Neuroscience.

GitHub: https://github.com/ricardoV94/
Twitter: https://twitter.com/RicardoV944
Website: https://ricardov94.github.io/posts/
PyMC Labs: https://www.pymc-labs.io  

#bayesian #statistics #python
```
