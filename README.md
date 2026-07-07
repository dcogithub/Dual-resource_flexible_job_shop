
Data and results for "A two-stage constraint programming-based heuristic for the dual-resource flexible job shop problem".
Computers & Operations Research.
--------------------------------------------------------------------------------------------------------------------------------------------------------------
This repository contains the data used for the article "**A two-stage constraint programming-based heuristic for the dual-resource flexible job shop problem**". 


This paper addresses the Dual-Resource Constrained Flexible Job Shop Scheduling Problem (DRCFJSP) with heterogeneous labor, arbitrary non-linear job routes, and operation-level flexibility in both machine and worker assignments. These modelling features yield a highly expressive but computationally challenging makespan-minimization problem for which Mixed-Integer Linear Programming (MILP) approaches often struggle to find feasible solutions for medium- and large-scale
instances. Leveraging the strong performance of Constraint Programming in complex scheduling, we develop a novel CP formulation solved with IBM ILOG CP Optimizer. To enhance escalability, we propose a hybrid two-layer solution strategy that decomposes the problem into
sequential machine- and worker-assignment phases, both relying on the same CP model with distinct parametrizations. The first layer assigns machine under relaxed worker availability, while the second
resolves worker allocations via a pseudo-machine FJSP that preserves feasibility through extended technological precedence constraints. Experiments on a new benchmark of 30 DRCFJSP instances, derived from a well-known FJSP dataset, show that the proposed method significantly outperforms the direct application of the CP model in both time and solution quality.


The data of instances are stored in the folder **Data**. The results of experiments are stored in the folder **Results**. 




