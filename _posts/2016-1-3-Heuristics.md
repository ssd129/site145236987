---
layout: post
title: Classification of Mathematical Optimization Problems and Algorithms. 
---

 An mathematical optimization problem is the problem of finding the best solution from all feasible solutions. Optimization problems can be divided into categories depending on whether the variables, constraints, objective functions and data.
 
 ![Types of problems](https://raw.githubusercontent.com/skalaouzis/skalaouzis.github.io/master/images/%CE%A7%CF%89%CF%81%CE%AF%CF%82%20%CF%84%CE%AF%CF%84%CE%BB%CE%BF.png)
 
* Continuous Optimization versus Discrete Optimization

Some models only make sense if the variables take on values from a discrete set, often a subset of integers, whereas other models contain variables that can take on any real value. Models with discrete variables are discrete optimization problems; models with continuous variables are continuous optimization problems. Continuous optimization problems tend to be easier to solve than discrete optimization problems; the smoothness of the functions means that the objective function and constraint function values at a point xx can be used to deduce information about points in a neighborhood of xx. However, improvements in algorithms coupled with advancements in computing technology have dramatically increased the size and complexity of discrete optimization problems that can be solved efficiently. Continuous optimization algorithms are important in discrete optimization because many discrete optimization algorithms generate a sequence of continuous subproblems.

* Unconstrained Optimization versus Constrained Optimization

Another important distinction is between problems in which there are no constraints on the variables and problems in which there are constraints on the variables. Unconstrained optimization problems arise directly in many practical applications; they also arise in the reformulation of constrained optimization problems in which the constraints are replaced by a penalty term in the objective function. Constrained optimization problems arise from applications in which there are explicit constraints on the variables. The constraints on the variables can vary widely from simple bounds to systems of equalities and inequalities that model complex relationships among the variables. Constrained optimization problems can be furthered classified according to the nature of the constraints (e.g., linear, nonlinear, convex) and the smoothness of the functions (e.g., differentiable or nondifferentiable).

* None, One or Many Objectives

Most optimization problems have a single objective function. There are interesting cases when optimization problems have no objective function or multiple objective functions. Feasibility problems are problems in which the goal is to find values for the variables that satisfy the constraints of a model with no particular objective to optimize. Complementarity problems are pervasive in engineering and economics. The goal is to find a solution that satisfies the complementarity conditions. Multi-objective optimization problems arise in many fields, such as engineering, economics, and logistics, when optimal decisions need to be taken in the presence of trade-offs between two or more conflicting objectives. For example, developing a new component might involve minimizing weight while maximizing strength or choosing a portfolio might involve maximizing the expected return while minimizing the risk. In practice, problems with multiple objectives often are reformulated as single objective problems by either forming a weighted combination of the different objectives or by replacing some of the objectives by constraints.

* Deterministic Optimization versus Stochastic Optimization

In deterministic optimization, it is assumed that the data for the given problem are known accurately. However, for many actual problems, the data cannot be known accurately for a variety of reasons. The first reason is due to simple measurement error. The second and more fundamental reason is that some data represent information about the future (e. g., product demand or price for a future time period) and simply cannot be known with certainty. In optimization under uncertainty, or stochastic optimization, the uncertainty is incorporated into the model. Robust optimization techniques can be used when the parameters are known only within certain bounds; the goal is to find a solution that is feasible for all data and optimal in some sense. Stochastic programming models take advantage of the fact that probability distributions governing the data are known or can be estimated; the goal is to find some policy that is feasible for all (or almost all) the possible data instances and optimizes the expected performance of the model.

To solve problems, researchers may use algorithms that terminate in a finite number of steps, or iterative methods that converge to a solution (on some specified class of problems), or heuristics that may provide approximate solutions to some problems (although their iterates need not converge).

![Different classifications of metaheuristics](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Metaheuristics_classification.svg/630px-Metaheuristics_classification.svg.png)

* Particle Swarm Optimization (PSO) is a computational method for multi-parameter optimization which also uses population-based approach. A population (swarm) of candidate solutions (particles) moves in the search space, and the movement of the particles is influenced both by their own best known position and swarm's global best known position. PSO is often more computationally efficient especially in unconstrained problems with continuous variables.

[Particle Swarm Optimization Algorithm](https://www.youtube.com/watch?v=HT15dq9Af7Q)

A very simple PSO code can be obtained with an example in MATLAB environment to this [link](http://www.mathworks.com/help/gads/particle-swarm-optimization-algorithm.html).

* Ant Colony Optimization (ACO) studies artificial systems that take inspiration from the behavior of real ant colonies and which are used to solve constrained problems with discrete variables optimization problems (which can be reduced to finding good paths through graphs).

[Ant Colony Optimization Algorithm](https://www.youtube.com/watch?v=D58nLNLkb0I)

A very simple ACO code can be obtained with an example in MATLAB environment to this [link](http://www.aco-metaheuristic.org/aco-code/).

* Nondominated Sorting Genetic Algorithm II (NSGA II) is a fast and elitist multiobjective genetic algorithm for constrained problems with continuous variables.

A very simple NSGA II code can be obtained with an example in MATLAB environment to this [link](https://www.mathworks.com/matlabcentral/fileexchange/49806-matlab-code-for-constrained-nsga-ii-dr-s-baskar--s-tamilselvi-and-p-r-varshini).

unconstrained problems with discrete variables.



