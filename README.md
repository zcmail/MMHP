# Code for MMHP model

This repository contains the code for the following paper including numerical examples and real data study:

- Jing wu, Tian Zheng, Modeling Sporadic Event Dynamics with Markov-Modulated Hawkes Processes.

In this paper, we propose a Markov Modulated Hawkes Process (MMHP) model for modeling such a mixture of different event dynamics and develop corresponding inference algorithms. Numerical experiments using synthetic data and data from an animal behavior study demonstrate that MMHP with the proposed estimation algorithms consistently re- cover the true hidden state process in simulations, and separately captures distinct event dynamics that reveal interesting social structure in the real data.

The structure of this repository is as follows:

- code
	- Rmd/: the detailed R scripts withe explanation that to generate the results shown in the paper. 

- lib
	- Rcode/: directory containing the R functions that are called from `main.Rmd` scripts. 

- data
    - Rdata/: include 10 cohorts mice interaction data
  
- figures
	-  figures/: Directory containing figures generated by the scripts and shown in the paper.

