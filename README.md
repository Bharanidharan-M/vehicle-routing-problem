Vehicle Routing Problem (VRP) Solver
Project Description
This project implements a solution for the Vehicle Routing Problem (VRP), a classic optimization challenge in logistics and transportation. The goal is to efficiently route a fleet of vehicles to serve a set of locations, minimizing the total travel distance while balancing workload among vehicles.

The project uses a Genetic Algorithm (GA) to optimize routes for multiple vehicles visiting randomly generated locations.

Features
Randomized Problem Setup: Locations and depots are generated dynamically for flexible problem configurations.
Optimization Framework: Utilizes the deap library for implementing Genetic Algorithms.
Visualization: Outputs optimized routes in a graphical format using Matplotlib.
Installation
Ensure you have Python installed. Then, install the required dependencies using:

bash
Copy code
pip install matplotlib deap
How It Works
Problem Initialization:

Randomly generates n locations within a 2D space (default: 20 locations).
Defines a central depot and the number of vehicles available for routing.
Genetic Algorithm Setup:

Represents solutions (routes) as individuals in a population.
Uses a custom fitness function to evaluate solutions based on:
Total distance traveled.
Workload balance among vehicles.
Optimization:

Performs selection, crossover, and mutation operations iteratively.
Produces a set of optimized routes over generations.
Visualization:

Plots the optimized vehicle routes on a 2D graph for easy interpretation.
Usage
Run the notebook to execute the solution. Key steps include:

Define the number of locations and vehicles.
Customize Genetic Algorithm parameters such as population size and mutation probability.
View the optimized routing visualization.
Results
The solution outputs:

Optimized routes for the fleet of vehicles.
Total travel distance and balance metrics.
Dependencies
Python 3.7+
matplotlib
deap
numpy
