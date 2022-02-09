# Stochastic Processes: Simulation and Tracking of a fish school through statistical processes

*Stochastic Processes: Tracking of a fish school*,
Sep 2018 – Jan 2019

__Tasks:__ In the context of the Stocastic Process course. We implement a simulation of tracking a fish school when confronted to a predator.

## Problem solving strategy:

__Part1:__ Fishes motion statistical characterisation 

* Setting the problem: N empirical observation, speed as random variable, known parametric data model
* Mathematical development for the Maximum likelyhood estimator and the method of moment
* Python simulations for deciding the best estimator compared to data

![fish_param_simu1](https://user-images.githubusercontent.com/48290004/153193937-77cc0e1e-b656-425b-9bdc-1e082c5d6ff3.PNG)
*Fig.1 -  Comparison of the average on 500 test evaluation of S&#770; on the left and K&#770; on the right with its real value. In red the MLE evaluation and in blue the Moment method*

![fish_param_simu2](https://user-images.githubusercontent.com/48290004/153193949-e6c76c4d-e15b-448e-872d-88417b95f20d.PNG)
*Fig.2 - Standard deviation of determined S&#770; on the left and K&#770; on the right. In red the MLE evaluation and in blue the Moment method*

__Part2:__ Fish tracking through time

* Reformulation of the problem as a stochastic process
* Implementation of a Monte Carlo filter.
* Matlab simulations

![fish_stoch_simu1](https://user-images.githubusercontent.com/48290004/153193960-9480ae88-3ced-442c-806d-006b1b31caa1.PNG)
*Fig.3 - On the left figure , the evolution of the MLE when the number of particle increases for a determined
σ²obs=0.5 and a time step=0.05s. On the right one, evolution of the MLE when the time step increases with the
same σ²obs=0.5 and for 500 particles.*

*Report in English availalbe on Github.*
