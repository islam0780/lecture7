# Activities

## Task 1

- Refer to te following link. Explain the Dijkstra's Shortest Path Algorithm.
  https://www.freecodecamp.org/news/dijkstras-shortest-path-algorithm-visual-introduction/

  // Dijkstra's Shortest Path Algorithm is a method for finding the shortest path between two nodes in a graph. The algorithm works by starting at the initial node and iteratively visiting the neighboring nodes, updating their distance from the initial node if a shorter path is found. This process is repeated until the destination node is reached or all reachable nodes have been visited. The algorithm ensures that the shortest path to each visited node is found, resulting in the shortest path overall. The algorithm is commonly used in routing and navigation applications.

## Task 2

- Explain how the code in `./src/dspa.cpp` works. Refer to the following link:
  https://www.geeksforgeeks.org/c-program-for-dijkstras-shortest-path-algorithm-greedy-algo-7/

// The code is an implementation of Dijkstra's Shortest Path Algorithm in C++. The algorithm works by taking a graph represented by an adjacency matrix as input, along with a source vertex. It then initializes an array to hold the distance to each vertex, with the source vertex having a distance of 0 and all other vertices having a distance of infinity.

The algorithm then iteratively selects the vertex with the smallest distance that has not yet been visited, updates the distance of its neighbors if a shorter path is found, and marks the vertex as visited. This process is repeated until all vertices have been visited or the destination vertex has been reached.

The code uses a priority queue to efficiently select the vertex with the smallest distance, and an array to keep track of which vertices have been visited. The final array of distances is returned as output.



## Task 3

- Explain how the code in `./src/mspt.cpp` works. Refer to the following link:
  https://www.tutorialspoint.com/kruskal-s-minimum-spanning-tree-algorithm-greedy-algorithm-in-cplusplus#

//The code  is an implementation of Kruskal's algorithm for finding the minimum spanning tree of a weighted undirected graph. The algorithm works by iteratively adding the edges of the graph in ascending order of weight, while ensuring that the added edge does not create a cycle in the tree.

The code first reads in the number of vertices and edges of the graph, and then reads in the edge list with each edge represented by its endpoints and weight. It then sorts the edge list in ascending order of weight using the sort() function.

The algorithm then creates a disjoint set data structure to keep track of which vertices belong to the same connected component, initially assigning each vertex to its own set. It then iterates through the sorted edge list, adding each edge to the tree if it connects two disjoint sets, and merging the sets if necessary. This process continues until all vertices are in the same set, i.e., the tree is complete.

The code uses the union() and find() operations on the disjoint set data structure to efficiently determine if two vertices are in the same set and merge them if necessary. It also uses a vector to keep track of the edges in the minimum spanning tree.

## Task 4: Individual (at home)

- Refer to te following link. Explain when to use the greedy methods and when to avoid them.
  https://www.freecodecamp.org/news/when-to-use-greedy-algorithms/

In general, greedy algorithms are useful when the problem you're trying to solve has the following properties:

1. Optimal substructure: The problem can be broken down into subproblems, and the solution to each subproblem contributes to the solution of the overall problem.

2. Greedy choice property: At each step, you can make the locally optimal choice, and it will lead to a globally optimal solution.

When these properties hold, a greedy algorithm can often be used to quickly find an optimal solution.

However, there are some cases where greedy algorithms should be avoided:

1. When the problem doesn't have the optimal substructure property: If the solution to a subproblem doesn't contribute to the overall solution, then a greedy algorithm may not be able to find the optimal solution.

2. When the greedy choice property doesn't hold: In some cases, making the locally optimal choice at each step won't necessarily lead to a globally optimal solution. In these cases, a different algorithm may be needed.

3. When the problem has constraints: Greedy algorithms don't work well with problems that have constraints, such as knapsack problems, because they may not consider all possible solutions.

4. When the problem requires exact solutions: Greedy algorithms often find approximate solutions, rather than exact solutions. If an exact solution is required, a different algorithm may be needed.

Overall, greedy algorithms are a useful tool in algorithm design, but they should be used with caution, and their suitability for a particular problem should be carefully considered before use.
## Link(s)

- https://cpp.sh/
