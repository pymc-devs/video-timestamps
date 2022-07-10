```txt

Speaker: Ricardo Vieira

Title:  PyMC, Aesara and Aeppl: The New Kids on The Block

Video: https://youtu.be/_APNiXTfYJw

## Resources
- Meetup event: https://www.meetup.com/pymc-online-meetup/events/286748916/
- Slides:
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
08:30 Ricardo begins presentation
00:00 Help us add more timestamps here



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
