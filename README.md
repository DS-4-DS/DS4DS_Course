Data Science for Dynamical Systems Course Materials
=======================================
[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Course Content

You can find the video lectures on [YouTube](https://www.youtube.com/@UPB_DS4DS-bu8ec/playlists).

The associated [**Julia**](https://julialang.org/) code (in the form of Jupyter Notebooks) can be found in the "notebooks" folder. In case a certain package is missing in your Julia version, you can simply add a cell before the first one containing the two code lines\
`using Pkg`\
`Pkg.add("name_of_package")`

References to related literature can be found at the end of this Readme file.

## Section 00: Course introduction
* [Data Science for Dynamical Systems Course Introduction 1 (DS4DS 0.01)](https://www.youtube.com/watch?v=KftMLQquoPo&list=PLg6FTHy3zJjzqJ76VHF9bMGEKrKR_KgNC&index=1)
* [Data Science for Dynamical Systems Course Introduction 2 (DS4DS 0.02)](https://www.youtube.com/watch?v=ihVYAnBUAaA&list=PLg6FTHy3zJjzqJ76VHF9bMGEKrKR_KgNC&index=2)

## Section 01: Dynamical Modeling Fundamentals
* Week 1:
  * [Solution of scalar linear autonomous ODEs (DS4DS 1.01)](https://www.youtube.com/watch?v=48FVrkGrJkA&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=1)
  * [Solution of vectorial linear autonomous ODEs (DS4DS 1.02)](https://www.youtube.com/watch?v=p_phobJmjCk&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=2)
  * [Matrix exponential solution via diagonalization (DS4DS 1.03)](https://www.youtube.com/watch?v=SUuSwOYeAKU&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=3)
  * [Spring-mass-damper as an autonomous state-space system example (DS4DS 1.04)](https://www.youtube.com/watch?v=D4yAvFUcENQ&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=4)
  * [State stability of autonomous state-space systems (DS4DS 1.05)](https://www.youtube.com/watch?v=FWX_z3zTGss&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=5)
  * [Nonlinear ODEs (1.06)](https://www.youtube.com/watch?v=WecRnf3vAZo&list=PLg6FTHy3zJjxvWhKhME-R6z_WaX5MQ-dH&index=6)

* Week 2:
  * [Numerical solutions of ODEs 1 (DS4DS 1.07)](https://www.youtube.com/watch?v=XHarMmETHkE)
  * [Numerical solutions of ODEs 2 (DS4DS 1.08)](https://www.youtube.com/watch?v=ikOcwSOyiCI)
  * [Numerical solutions of ODEs 3 (DS4DS 1.09)](https://www.youtube.com/watch?v=yG2J7Zj1H9E)
  * [State-space models with inputs (DS4DS 1.10)](https://www.youtube.com/watch?v=7cLYJrGazXg)
  * [Exact solution of linear state-space models (DS4DS 1.11)](https://www.youtube.com/watch?v=HtIkqjm1w5w)
  * [Observability 1 (DS4DS 1.12)](https://www.youtube.com/watch?v=BnT62ol7zvA)
  * [Observability 2 (DS4DS 1.13)](https://www.youtube.com/watch?v=A9Zc21IzLjA)
  * [Observability 3 (DS4DS 1.14)](https://www.youtube.com/watch?v=IKXNPHASATg)
  * [Discrete dynamical systems (DS4DS 1.15)](https://www.youtube.com/watch?v=Ew3y1SGlVQc)
   
* Week 3:
  * [Partial differential equations: Introduction (DS4DS 1.16)](https://www.youtube.com/watch?v=O0aNsfJ-peg)
  * [Partial differential equations: Derivation of the heat equation (DS4DS 1.17)](https://www.youtube.com/watch?v=_qM3NP4sgO8)
  * [Partial differential equations: Spatial discretization (DS4DS 1.18)](https://www.youtube.com/watch?v=AJz53LGRa1s)
  * [Partial differential equations: Discretization in space and time (DS4DS 1.19)](https://www.youtube.com/watch?v=c_jUfFBBvpQ)

## Section 02: Linear Model Identification
* Week 4:
  * [Linear model identification: intro part 1/2 (DS4DS 2.01)](https://www.youtube.com/watch?v=oFVnPJbi7Tg&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=1)
  * [Linear model identification: intro part 2/2 (DS4DS 2.02)](https://www.youtube.com/watch?v=H5bZ2to1ono&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=2)
  * [Linear least squares solution (DS4DS 2.03)](https://www.youtube.com/watch?v=1c1tMY0m3vE&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=3)
  * [Ordinary least squares: static example (DS4DS 2.04)](https://www.youtube.com/watch?v=Mm92nd9lkDc&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=4)
  * [Ordinary least squares: bias (DS4DS 2.05)](https://www.youtube.com/watch?v=hd9POUlZR-Q&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=5)
  * [Ordinary least squares: covariance (DS4DS 2.06)](https://www.youtube.com/watch?v=b_OSb7g5C40&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=6)
  * [Ordinary least squares: consistency (DS4DS 2.07)](https://www.youtube.com/watch?v=-3hS0ScYaaM&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=7)
 
* Week 5:
  * [Multicollinearity (DS4DS 2.08)](https://www.youtube.com/watch?v=YoG0IsghOhU&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=8)
  * [Ridge regression (DS4DS 2.09)](https://www.youtube.com/watch?v=eevhvtuEyPY&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=9)
  * [Weighted least squares: motivation & solution (DS4DS 2.10)](https://www.youtube.com/watch?v=cjWvy1iCEiE&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=10)
  * [Weighted least squares: example (DS4DS 2.11)](https://www.youtube.com/watch?v=WGXFemrKiJ0&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=11)
  * [Recursive least squares: derivation part 1/2 (DS4DS 2.12)](https://www.youtube.com/watch?v=SgUhJj1FvDE&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=12)
  * [Recursive least squares: derivation part 2/2 (DS4DS 2.13)](https://www.youtube.com/watch?v=RVvlsHdXyyU&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=13)
  * [Recursive least squares: exponential forgetting (DS4DS 2.14)](https://www.youtube.com/watch?v=4j1_Ux6_rOY&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=14)
  * [Recursive least squares: example (DS4DS 2.15)](https://www.youtube.com/watch?v=M5QYofnx1dg&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=15)
 
* Week 6:
  * [Ordinary Least Squares for Dynamical Systems: Introduction (DS4DS 2.16)](https://www.youtube.com/watch?v=yuLsDQFusrI&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=16)
  * [Ordinary Least Squares for Dynamical Systems: Example (DS4DS 2.17)](https://www.youtube.com/watch?v=6LitkQ2QTos&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=17)
  * [Ordinary Least Squares for Dynamical Systems: Limitations (DS4DS 2.18)](https://www.youtube.com/watch?v=HIezurtcoJc&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=18)
  * [Singular Value Decomposition: Motivation (DS4DS 2.19)](https://www.youtube.com/watch?v=8NAZZvM4cMY&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=19)
  * [Singular Value Decomposition: Interpretation (DS4DS 2.20)](https://www.youtube.com/watch?v=LNDS__ucMmk&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=20)
  * [Eigendecomposition of continuous and discrete-time dynamical systems (DS4DS 2.21)](https://www.youtube.com/watch?v=SA_hRTwZhHU&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=21)
  * [Dynamic Mode Decomposition: Concept (DS4DS 2.22)](https://www.youtube.com/watch?v=-QWlSJGRzzk&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=22)
  * [Dynamic Mode Decomposition: Efficient computation (DS4DS 2.23) ](https://www.youtube.com/watch?v=xzyQxCiEB7w&list=PLg6FTHy3zJjzWOkG2cnJM_j6tKFyjLSy9&index=23)

## Section 03: Optimization for Machine Learning
* Week 7:
  * [Training nonlinear models (DS4DS 3.01)](https://www.youtube.com/watch?v=Yp7BWq5cJec&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7)
  * [The hypothesis space (DS4DS 3.02)](https://www.youtube.com/watch?v=nEFZZfor8OY&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=2)
  * [Gradient descent 1 (DS4DS 3.03)](https://www.youtube.com/watch?v=mZ0vn2cYxQc&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=3)
  * [Gradient descent 2 (DS4DS 3.04)](https://www.youtube.com/watch?v=7asVgXqfkFo&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=4)
  * [Gradient descent 3 (DS4DS 3.05)](https://www.youtube.com/watch?v=4F6yFASvx1c&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=5)
  * [Gradient descent 4 (DS4DS 3.06)](https://www.youtube.com/watch?v=E2fCTUF9nYc&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=6)
  * [The Armijo and Wolfe conditions (DS4DS 3.07)](https://www.youtube.com/watch?v=Jxh2kqVz6lk&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=7)
  * [Stochastic gradient descent (DS4DS 3.08)](https://www.youtube.com/watch?v=iZ5rGdUcDRc&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=8)
 
* Week 8:
  * [Momentum (DS4DS 3.09)](https://www.youtube.com/watch?v=NuFWEZYayUI&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=9)
  * [Convergence rates (DS4DS 3.10)](https://www.youtube.com/watch?v=Ococ1-rrK9c&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=10)
  * [Newton's method (DS4DS 3.11)](https://www.youtube.com/watch?v=7INmTFzPDsg&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=11)
  * [Differentiation Techniques: Overview (DS4DS 3.12)](https://www.youtube.com/watch?v=hBEQbPkWrwk&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=12)
  * [Symbolic Differentiation (DS4DS 3.13)](https://www.youtube.com/watch?v=aBxnOUGq2ug&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=13)
  * [Algorithmic Differentiation: Forward mode (DS4DS 3.14)](https://www.youtube.com/watch?v=zQ9f6xpYEPw&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=14)
  * [Algorithmic Differentiation: Backward mode (DS4DS 3.15)](https://www.youtube.com/watch?v=hg33342oeTA&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=15)
 
* Week 9:
  * [Constrained optimization 1 (DS4DS 3.16)](https://www.youtube.com/watch?v=qQiVFvv2uiw&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=16)
  * [Constrained optimization 2 (DS4DS 3.17)](https://www.youtube.com/watch?v=inqmExLG11c&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=17)
  * [Constrained optimization 3 (DS4DS 3.18)](https://www.youtube.com/watch?v=yYuV-vBa7M8&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=18)
  * [Penalty methods and Sequential Quadratic Programming (DS4DS 3.19)](https://www.youtube.com/watch?v=F21CocZHpQs&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=19)
  * [The active set method 1 (DS4DS 3.20)](https://www.youtube.com/watch?v=cL5Djfu0pUY&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=20)
  * [The active set method 2 (DS4DS 3.21)](https://www.youtube.com/watch?v=c4N0oKvlp5s&list=PLg6FTHy3zJjws0hwWOa-cADy2aK5q_FM7&index=21)

## Section 04: Nonlinear Model Identification

* Week 10:
  * [Optimization-based parameter identification (DS4DS 4.01)](https://www.youtube.com/watch?v=Bn0SGV_5RMU&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=1)
  * [Impact of the prediction horizon in data-driven modeling (DS4DS 4.02)](https://www.youtube.com/watch?v=OmeEf-GHdfQ&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=2)
  * [Nonlinear prediction error method identification (DS4DS 4.03)](https://www.youtube.com/watch?v=dB0SY6tBPTU&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=3)
  * [Global vs. local optima in nonlinear data-driven modeling (DS4DS 4.04)](https://www.youtube.com/watch?v=PIrwCp8m1Ow&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=4)
  * [Identification of an unknown initial state (DS4DS 4.05)](https://www.youtube.com/watch?v=rCei6XlOv7A&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=5)
  * [Utilizing constrained optimization for incorporating a priori knowledge (DS4DS 4.06)](https://www.youtube.com/watch?v=h_AtcsE2tS0&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=6)
 
* Week 11:
  * [Neural ordinary differential equations - NODEs (DS4DS 4.07)](https://www.youtube.com/watch?v=s3YTiV4EBkg&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=7)
  * [Sampled input data for NODE modeling (DS4DS 4.08)](https://www.youtube.com/watch?v=OhLC4bf8e50&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=8)
  * [Hammerstein-Wiener models in NODEs (DS4DS 4.09)](https://www.youtube.com/watch?v=Kz_4tqW3FCM&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=9)
  * [Extrapolation of data-driven dynamical models (DS4DS 4.10)](https://www.youtube.com/watch?v=FhqDpPmlypc&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=10)
  * [Discrete-time nonlinear system identification (DS4DS 4.11)](https://www.youtube.com/watch?v=s0XxdbuQWFU&list=PLg6FTHy3zJjyi-0pVsmA49erc-BvQvP7g&index=11)

## Section 05: Feature Engineering
* Week 12:
  * [Feature Engineering - Introduction (DS4DS 5.01)](https://www.youtube.com/watch?v=iAUNc1LT__U&list=PLg6FTHy3zJjxTq898AZKytAySDBe1VX-Y&index=1)
  * [Manual feature selection using dictionaries (DS4DS 5.02)](https://www.youtube.com/watch?v=DfbN8EVLJ58&list=PLg6FTHy3zJjxTq898AZKytAySDBe1VX-Y&index=2)
  * [Extracting linear features from data (DS4DS 5.03)](https://www.youtube.com/watch?v=bjbRHtwHKTw&list=PLg6FTHy3zJjxTq898AZKytAySDBe1VX-Y&index=3)
  * [Feature engineering using autoencoders (DS4DS 5.04)](https://www.youtube.com/watch?v=4fArw2O0vVM&list=PLg6FTHy3zJjxTq898AZKytAySDBe1VX-Y&index=4)
  * [The role of features in deep learning (DS4DS 5.05)](https://www.youtube.com/watch?v=6Hg9pIQEIO0&list=PLg6FTHy3zJjxTq898AZKytAySDBe1VX-Y&index=5)

## Section 06: Model Selection
* Week 13:
  * [Overfitting and the bias-variance tradeoff (DS4DS 6.01)](https://www.youtube.com/watch?v=jMg4h1G0cyg&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=1)
  * [Cross validation (DS4DS 6.02)](https://www.youtube.com/watch?v=MxTO4r8H2oI&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=2)
  * [Sparsity and the L1 norm (DS4DS 6.03)](https://www.youtube.com/watch?v=FbRTXh5r270&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=3)
  * [Subdifferentials of non-differentiable functions (DS4DS 6.04)](https://www.youtube.com/watch?v=aRHgvxNG7_o&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=4)
  * [The LASSO algorithm for model selection (DS4DS 6.05)](https://www.youtube.com/watch?v=0aYlO5FoRQ4&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=5)
  * [Sparse identification of nonlinear dynamics (SINDy) (DS4DS 6.06)](https://www.youtube.com/watch?v=0wF3zvdvgK4&list=PLg6FTHy3zJjzvsyH8xgDerpycWUBsGK0U&index=6)

## Section 07: Control
* Week 14:
  * [Optimal control - Introduction (DS4DS 7.01)](https://www.youtube.com/watch?v=6GSHAoLMsXs&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei)
  * [Optimal control in discrete time (DS4DS 7.02)](https://www.youtube.com/watch?v=KuAbISxSJQI&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=2)
  * [Optimal control of linear systems 1 - Dynamics (DS4DS 7.03)](https://www.youtube.com/watch?v=FKn9lJKVj1E&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=3)
  * [Optimal control of linear systems 2 - Objective function (DS4DS 7.04)](https://www.youtube.com/watch?v=3ZTWuTV55Kk&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=4)
  * [Optimal control of linear systems 3 - Example (DS4DS 7.05)](https://www.youtube.com/watch?v=131q4mBEid8&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=5)
  * [Linear model predictive control (DS4DS 7.06)](https://www.youtube.com/watch?v=F5Y-nFsRKts&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=6)
  * [Data-driven model predictive control using DMD (DS4DS 7.07)](https://www.youtube.com/watch?v=Z63Xl_Xy3Ts&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=7)
  * [Differential predictive control: introduction (DS4DS 7.08)](https://www.youtube.com/watch?v=eZLwms4nRu8&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=8)
  * [Differential predictive control: global vs. local optima (DS4DS 7.09)](https://www.youtube.com/watch?v=-D6puRAMTww&list=PLg6FTHy3zJjzJ8Ddui6ZwQpdMZeoqG1ei&index=9)

## Section 08: Koopman operator
* [An introduction to the Koopman Operator (DS4DS 8.01)](https://www.youtube.com/watch?v=bPvLRppwB9o&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=1)
* [Koopman operator: Spectral decomposition 1 (DS4DS 8.02)](https://www.youtube.com/watch?v=cbOFlNlJGI8&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=2)
* [Koopman operator: Spectral decomposition 2 (DS4DS 8.03)](https://www.youtube.com/watch?v=ZejyI4vYYE4&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=3)
* [Koopman: Observable functions (DS4DS 8.04)](https://www.youtube.com/watch?v=x8usQJ-u5-o&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=4)
* [Extended Dynamic Mode Decomposition 1 - Finite dimensional subspaces (DS4DS 8.05)](https://www.youtube.com/watch?v=GFk8TXJ3IOc&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=5)
* [Extended Dynamic Mode Decomposition 2 - The EDMD algorithm (DS4DS 8.06)](https://www.youtube.com/watch?v=lvRhlY22jWw&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=6)
* [Extended Dynamic Mode Decomposition 3 - Koopman eigenfunctions (DS4DS 8.07)](https://www.youtube.com/watch?v=ydLNaoyXwm0&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=7)
* [Extended Dynamic Mode Decomposition 4 - Koopman modes & Summary (DS4DS 8.08)](https://www.youtube.com/watch?v=lnNR2jYyKxI&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=8)
* [Dynamic Mode Decomposition as a special case of EDMD (DS4DS 8.09)](https://www.youtube.com/watch?v=mHIy4II-aO4&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=9)
* [kernel EDMD 1 - Motivation & kernel trick (DS4DS 8.10)](https://www.youtube.com/watch?v=X3JWOtz4peI&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=10)
* [kernel EDMD 2 - Main algorithm (DS4DS 8.11)](https://www.youtube.com/watch?v=kAXRZrIxxQ0&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=11)
* [kernel EDMD 3 - Koopman eigenfunctions and modes (DS4DS 8.12)](https://www.youtube.com/watch?v=b1E0fdCK3i0&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=12)
* [The Koopman Generator (DS4DS 8.13)](https://www.youtube.com/watch?v=tUGn1U9mlHw&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=13)
* [Extended DMD for the Koopman Generator (DS4DS 8.14)](https://www.youtube.com/watch?v=8bOerAx_MzE&list=PLg6FTHy3zJjy9GLiVJlxyLSZeSCTVnYtz&index=14)
 
# Related literature
* Data science and machine learning:
  * Y. S. Abu-Mostafa, M. Magdon-Ismail and H.-T. Lin. "Learning from data: A short course." AMLBook, 2012. ([URL](https://work.caltech.edu/telecourse))
  * S. L. Brunton and J. N. Kutz. "Data-Driven Science and Engineering." Cambridge University Press, 2019. ([DOI](https://doi.org/10.1017/9781108380690))
  * C. M. Bishop. "Pattern Recognition and Machine Learning." Springer, 2007. ([URL](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf))
    
* Dynamical systems and system identification:
  * R. Isermann and M. Münchhof. "Identification of Dynamic Systems." Springer, 2011. ([DOI](https://doi.org/10.1007/978-3-540-78879-9))
  * O. Nelles. "Nonlinear System Identification." Springer, 2001. ([DOI](https://doi.org/10.1007/978-3-030-47439-3))

* Optimization
  * G. Nocedal and S. J. Wright. "Numerical Optimization." ([DOI](https://doi.org/10.1007/978-0-387-40065-5))
  * _The book by Nelles also has an extensive introduction to optimization._
