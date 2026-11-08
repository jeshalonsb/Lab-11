Lab 11 README

How does each pathfinding algorithm calculate and prioritize paths?

BFS: checks nearby cells and tries to find shortest path
Dijkstra: lowest cost
A*: uses heuristic


What challenges arise when dynamically updating obstacles in real-time?
Obstacle blocking b\c it forces algorithm to make a new path. If you make too many paths, it can overload performance 


Which algorithm should you choose for larger grids or open-world settings?
A*: uses heuristic to make it cost efficient instead of trying to make it thru each block to find the shortest path. 

How would you add weighted cells for difficult terrain?
Different cells will have different costs that the algorithm can go and find the lowest costing cells to make it 