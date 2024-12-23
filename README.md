# Maze-Solver
Created an agent robot that solves mazes that you create

Created a Goal-Based Agent to find the goal spot in a maze. Tested different types of searching algorithms for the agent
- depth-first search
- breadth-first search
- greedy best-first search
- A* search

The agent has a map of the maze it is in and the environment is assumed to be deterministic, discrete, and known. The agent must use the map to plan a path through the maze from the starting location  𝑆  to the goal location  𝐺 . This is a planing exercise for a goal-based agent, so you do not need to implement an environment, just use the map to search for a path. Once the plan is made, the agent in a deterministic environment (i.e., the transition function is deterministic with the outcome of each state/action pair fixed and no randomness) can just follow the path and does not need to care about the percepts. This is also called an open-loop system. The execution phase is trivial and we do not implement it in this exercise.

Tree search algorithm implementations that you find online and used in general algorithms courses have often a different aim. These algorithms assume that you already have a tree in memory. We are interested in dynamically creating a search tree with the aim of finding a good/the best path from the root noteto the goal state. Follow the pseudo code presented in the text book (and replicated in the slides) closely. Ideally, we would like to search only a small part of the maze, i.e., create a search tree with as few nodes as possible.


