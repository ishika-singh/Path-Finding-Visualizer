A* Path Finding Algorithm


This code implements a visualizer for the A* pathfinding algorithm using Pygame,
a Python library for creating graphical applications. 
The A* algorithm is used to find the shortest path between two points on a grid while avoiding obstacles.

The formula used here is F(n) = G(n) + H(n) where,
G(n) => The G score is the shortest distance between start node to the current node.
H(n) => The H score is the heuristic the estimates the distance of end node from the start node.
F(n) => The F score is the addition of both G score and H score.
