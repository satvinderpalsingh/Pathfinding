# Pathfinding
->Path visualization tool using python and pygame.
->Visualizing shortest path in a matrix from one block to another block in a matrix.
->Implemented A* star algorithm for finding paths.

A* is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency.
A* is an informed search algorithm, or a best-first search, meaning that it is formulated in terms of weighted graphs: starting from a specific starting node of a graph, it aims to find a path to the given goal node having the smallest cost (least distance travelled, shortest time, etc.). It does this by maintaining a tree of paths originating at the start node and extending those paths one edge at a time until its termination criterion is satisfied.

#Path visualising Matrix Description
1.RED = represent the node have been looked upon and we are not gone look it again
2.GREEN = represent the node is in a open set and can we used agin to find the path to destination node
3.WHITE = represent the node has not been visited ot looked yet
4.BLACK = represent the node is a barrier and we need to avoid that node in out alogorithm cant use that node to visit
5.PURPLE = represent shortest path from start node to destination node 
6.ORANGE = start node 
7.TURQUOISE = represnt the end color
![Capture](https://user-images.githubusercontent.com/56163417/122709773-94410980-d27c-11eb-93d7-014d8a964813.PNG)


