# Resource-Constrained Project Scheduling Problem (RCPSP) Genetic Algorithm
Overview
This Python code provides a genetic algorithm (GA) solution to the Resource-Constrained Project Scheduling Problem (RCPSP). The RCPSP involves scheduling a set of activities with resource and time constraints to minimize project duration.

Problem Description
In this specific implementation:

There are six activities: a, b, c, d, e, and f.
Each activity has specified resource requirements and duration.
The total available resources at any given time are limited to 4 units.
Code Structure
The code is structured as follows:

Problem Definition

The activities are defined with their resource requirements and durations.
The total available resources are specified.
Initialization

An initial population of schedules is generated randomly.
Genetic Algorithm

The GA runs for a specified number of generations.
In each generation:
The fitness of each schedule is evaluated based on project duration while respecting resource constraints.
Parents are selected using tournament selection.
Crossover is performed to create two offspring.
Mutation is applied with a small probability.
Both offspring are added to the new population.
The population is sorted by fitness, and the top individuals are retained to maintain the population size.
Result

The best schedule, which minimizes project duration, is selected as the output.
Usage
Specify the number of generations and population size in the genetic_algorithm function.
Run the code, and it will output the best schedule and its corresponding project duration.
Customization
You can modify the problem parameters by changing the activity definitions and resource constraints.
Adjust the GA parameters (e.g., mutation rate) as needed for your specific problem.
This code provides a basic framework for solving the RCPSP using a genetic algorithm. Further customization and fine-tuning may be required for more complex instances of the problem.


![image](https://github.com/dasslerrr/RCPSP-with-Genetic-Algorithm/assets/75805648/24bfe5f2-8af0-4475-a912-f6e75a7d1f95)

This Gantt chart-like visualization that shows the resource utilization over time for a project schedule. The x-axis represents the time, and the y-axis represents the resources. The bars of different heights and lengths represent the allocation of resources to various tasks over time. This type of visualization helps understand the resource constraints and how the resources are being used throughout the project timeline.

![image](https://github.com/akshayk7k/AI-RCPS-/blob/main/Figure_1.png)

This graph appears to be a directed acyclic graph (DAG) that represents the precedence relationships between different tasks or activities in your project. The nodes represent the tasks, and the directed edges between them indicate the dependencies. For example, task 1 must be completed before task 3 can start. This type of visualization helps understand the task dependencies and the flow of the project.

![image](https://github.com/akshayk7k/AI-RCPS-/blob/main/activity_graph.png)



