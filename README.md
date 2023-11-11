# Knapsack01
Here, the optimization codes for five well-known combinatorial problems, including Knapsack 0-1 (KP01), Facility Layout Planning (FLP), Construction Site Layout Planning (CSLP), Quadratic Assignment Problem (QAP), and Travelling Salesman Problem (TSP) are provided which have been written in C++ language programming. These codes can be used free of charge for academic purposes or comparative studies. Our solution approach in all of these problems is a metaheuristic algorithm, i.e., Simulated Annealing (SA).

- Codes for Knapsack Problem 0-1 (KP01):

1st single-solution based Simulated Annealing for 0-1 Knapsack Problem (SAKP01_1)

SAKP01_1 uses RISP for its initial solution generation and Sonuc_RI for its local search.

2nd single-solution based Simulated Annealing for 0-1 Knapsack Problem (SAKP01_2)

SAKP01_2 uses RISP for its initial solution generation and Zhan_RI for its local search.

3rd single-solution based Simulated Annealing for 0-1 Knapsack Problem (SAKP01_3)

SAKP01_3 uses GISP for its initial solution generation and GS for its local search.

Population-based Simulated Annealing for 0-1 Knapsack Problem (PSAKP01)

PSAKP01 uses both RISP & GISP for its initial solution generation and a mutation and crossover-based Zhan_RI for its local search.

- Codes for Stochastic Facility Layout Planning Problem (STFLP): 

Simulated Annealing for GSUA-STFLP (SA-GSUA-STFLP)

This algorithm solves the FLP with stochastic parameters, unequal area facilities, and grid system modeling by SA which is described in "Moradi, N. (2019). Stochastic Facility Layout Planning Problem: A Metaheuristic and Case Study. Iranian Journal of Optimization, 11(2), 229-241.".

- Codes for Construction Site Layout Planning (CSLP):

Simulated Annealing for CSLP (SACSLP)

This source code is about solving UA-CSLP using a Simulated Annealing optimization algorithm (SA). In this code, the example of (H. Li & Love, 1998), which can be developed easily, is solved. Also, this code can be used in order to compare the proposed algorithm with other solution techniques. This algorithm is provided in "Moradi, N., & Shadrokh, S. (2019). A simulated annealing optimization algorithm for equal and un-equal area construction site layout problem. International Journal of Research in Industrial Engineering, 8(2), 89-104.".

- Codes for Quadratic Assignment Problem (QAP):

Simulated Annealing for QAP (SAQAP)

SAQAP algorithm solves the QAP with a simple version of SA (non-greedy approach for the local search). The next versions of SA-based algorithms for QAP will be improved by using population-based and Reinforcement learning (RL) based approaches.

- Codes for Travelling Salesman Problem (TSP):

Simulated Annealing for TSP (SATSP)

SATSP algorithm solves the TSP with a simple version of SA (non-greedy approach for the local search). The next versions of SA-based algorithms for TSP will be improved by using population-based and Reinforcement learning (RL) based approaches.

​

Errors and questions are referred to:

Nima Moradi, 
