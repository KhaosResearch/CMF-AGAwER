# CMF-AGAwER


This is the implementation of a paper entitled Feature selection using classification error impurity and adaptive genetic algorithm with external repository. The proposed feature selection method (CMF-AGAwER) is a hybrid (ensemble + wrapper). The ensemble section combines the top 50 features ranked by Classification Error Impurity (CEI), a newly proposed frequency-based method, with the top 50 features ranked by Mutual Information (MI) and the top 50 features ranked by Fisher Ratio (FR). The wrapper section utilizes the Adaptive Genetic Algorithm with External Repository (AGAwER). AGAwER's primary contribution lies in its external repository, coupled with an adaptive strategy that adjusts crossover and mutation rates to enhance the exploration capability of genetic algorithms (GA).

Classification Error Impurity (CEI) is a frequency-based filter ranking method, which belongs to a series of frequency-based rankers:

1- [Mutual Congestion (MC)](https://www.sciencedirect.com/science/article/pii/S0888754318304245). Publication year: 2019

2- [Sorted Label Interference (SLI)](https://www.sciencedirect.com/science/article/pii/S0306437921000259#!). Publication year: 2021

3- [Sorted Label Interference-gamma (SLI-gamma)](https://link.springer.com/article/10.1007/s11227-022-04650-w). Publication year: 2022

4- [Extended Mutual Congestion (EMC)](https://https://www.sciencedirect.com/science/article/pii/S1568494622007487#!). Publication year: 2022

5- [Maximum Pattern Recognition (MPR)](https://www.sciencedirect.com/science/article/pii/S0957417424003865). Publication year: 2024

6- Distance-based Mutual Congestion (DMC). Publication year: Under Review

7- Classification Error Impurity (CEI). Publication year: Under Review

##################### Instruction #########################

After loading the corresponding dataset from your local drive:

1- Run lines 55-71 to calculate the summation of samples per label

2- Run lines 73-93 for Maximum Pattern Recognition (MPR)

3- Run lines 96-110 to create a dataset with top 20 features of MPR

4- Run lines 115-409 for Multi-objective Discrete Evolution Strategy and its corresponding functions

Cite this article

Hossein Nematzadeh, José García-Nieto, José F. Aldana-Montes, Ismael Navas-Delgado. Pattern recognition frequency-based feature selection with multi-objective discrete evolution strategy for high-dimensional medical datasets. Expert Systems with Applications, Volume 249, Part A, 2024, 123521, ISSN 0957-4174. https://doi.org/10.1016/j.eswa.2024.123521.
