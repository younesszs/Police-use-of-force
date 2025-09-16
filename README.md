
# A Mixed Integer Linear Programming Approach to Minimize Police Use-Of-Force

- The work proposes a mixed-integer linear programming (MILP) framework to reduce police use-of-force incidents. 
- The method models incidents with a multivariate Hawkes process and optimizes officer assignment networks through MILP. 
- By rewiring connections between officers, the framework minimizes the expected number of use-of-force events.


The repository introduces the code as well as the data. The code was already run in saved in Pickle files for reproducibility. The repository contains:
- Chicago complaint data for the Chicago Police Department.
- Indianapolis use-of-force data from the Indianapolis Metropolitan Police Department. 
- Massachusetts complaint & disciplinary data from the Massachusetts POST Commission. 
- Phoenix use-of-force incidents from Phoenix Police Department. 
- Seattle public use-of-force data from Seattle Police Department. 

Each directory contains the code in a Jupyter notebook, the pickle files of the results for reuse, as well as the different figures in EPS foramt. 

# Installation

- This code is run on Python 3.9.0 and CPLEX 22.1.1.0 
- IBM ILOG CPLEX Optimization Studio (full license). The free community edition of CPLEX is not sufficient due to its variable and problem size limits.
- PyTorch (for Hawkes process parameter estimation) 
- Standard Python libraries: `numpy`, `scipy`, `matplotlib`, `pandas`
