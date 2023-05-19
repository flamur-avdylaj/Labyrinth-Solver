# Labyrinth-Solver
In this code, each Cell object represents a coordinate (x, y) in the maze. We use a queue to store the cells to be visited next. 'visited' is a 2D array keeping
track of the cells we've already visited. 
We continue the process until we either visit all reachable cells (and find no path) or reach the end of the maze (and find a path).

This will print out whether a path exists, but not the path itself. If you want to find the actual path, you would need to store additional information,
such as the previous cell for each visited cell, then backtrack from the end to find the path.
