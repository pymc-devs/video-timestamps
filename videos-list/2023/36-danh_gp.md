Speaker: Danh Phan

Title: An Introduction to Multi-Output Gaussian Processes using PyMC

- Video: https://youtu.be/8YN7dLJlHIE
- Meetup: https://www.meetup.com/pymc-online-meetup/events/291618626/

## Event description:
Multi-output Gaussian processes have recently gained strong attention from researchers and have become an active research topic in machine learning’s multi-task learning. The advantage of multi-output Gaussian processes is their capacity to simultaneously learn and infer many outputs which have a similar source of uncertainty from inputs.

This talk presents to audiences how to build multi-output Gaussian processes in PyMC. It first introduces the concept of Gaussian processes (GPs) and multi-output GPs and how they can address real problems in several domains. It then shows how to implement multi-output GPs models such as the intrinsic coregionalization model (ICM) and the linear model of coregionalization (LCM) in Python using PyMC with real-world datasets.

The talk aims to get users quickly up and performing GPs, especially multi-output GPs using PyMC. Several examples with time-series datasets are used to illustrate different GPs features. This presentation will allow users to leverage GPs to analyze their data effectively.

## Discourse Discussion
https://discourse.pymc.io/t/pymcon-web-series-an-introduction-to-multi-output-gaussian-processes-using-pymc-feb-21st-10-pm-utc-2023/11395

## Timestamps
```
00:00 Ravin Kumar does introduction and background
02:18 Danh Phan instructions on using the workshop's repo
05:47 Part 1: Introduction to Gaussian processes (GPs) with PyMC
05:48 1.0 Intro
06:54 1.1 Bayesian Linear Regression
11:43 1.2 Gaussian Process
13:20 1.3 GP Mean and Covariance Functions
16:24 1.3 examples
15:56 2.0 Model implementation in PyMC
16:57 2.1 Bayesian Linear Regression
19:52 2.2 Gaussian Processes in PyMC
24:27 3.0 References
25:12 Q&A for Part 1
28:03 Part 2: Introduction to Multi-output Gaussian processes (MoGPs) with PyMC
28:18 1.0 Why MoGPs
31:08 1.1 Single-output Gaussian Process
32:31 1.2 Multiple-output Gaussian Process
34:53 2.0 Intrinsic Coregionalization Model (ICM)
36:00 2.1 ICM: one latent samples & covariance
39:21 2.2 ICM: two outputs, two laten samples & covariance
42:25 2.3 Kronecker product between matrices
43:58 2.4 ICM: covariances as Kronecker product
44:37 3.0 Linear Coregionalization Model (LCM)
45:11 3.1 LCM: covariance
45:41 4.0 PyMC Coregion kernel
46:18 5.0 Hadamard product between matrices
47:07 5.1 Kronecker to Hadamard product
49:52 Part 2 example: Intro
50:07 Part 2 example: Data prep & EDA
51:40 Part 2 example: ICM
56:39 Part 2 example: LCM
58:42 Author's example work
01:00:42 Sampling with nutpie
01:02:23 Q&A for part 2: How important the joint normality assumption (in enquirer's work)
01:04:47 Q&A for part 2: Business benefits of using MoGPs in the baseball example
01:11:07 Q&A for part 2: Validity of using MoGPs for sparse temporal data (crime)
01:13:43 Ravin Kumar closing
```
Help us add timestamps here: https://github.com/pymc-devs/video-timestamps

## Speaker bio:
xxx
xxx
xxx

## Speaker info: 
- GitHub: https://github.com/danhphan
- Twitter: https://twitter.com/danhpt 
- LinkedIn: https://www.linkedin.com/in/danhpt/

Part of PyMCon2023. 
More details at http://www.pymcon.com  

## Hashtags
#bayesian #statistics 
