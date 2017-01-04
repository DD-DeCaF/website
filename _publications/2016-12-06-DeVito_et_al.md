---
layout: publication
title: Optlang - An algebraic modeling language for mathematical optimization
authors: Jensen, Kristian and Cardoso, Joao G.R. and Sonnenschein, Nikolaus
journal: The Journal of Open Source Software
volume:
number:
pages:
year: 2016
doi: 10.21105/joss.00139
icon: mdi-file-document
---
Optlang is a Python package implementing a modeling language for solving mathematical optimization problems, i.e., maximizing or minimizing an objective function over a set of variables subject to a number of constraints. It provides a common native Python interface to a series of optimization tools, so different solver backends can be used and changed in a transparent way.
Optlang's object-oriented API takes advantage of the symbolic math library SymPy (Team 2016) to allow objective functions and constraints to be easily formulated algebraically from symbolic expressions of variables. Optlang targets scientists who can thus focus on formulating optimization problems based on mathematical equations derived from domain knowledge.
Solver interfaces can be added by subclassing the four main classes of the optlang API (Variable, Constraint, Objective, and Model) and implementing the relevant API functions.
