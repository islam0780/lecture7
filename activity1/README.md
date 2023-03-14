# Activities

## Task 1:

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Graph/GraphIntroSumm.html

 1. Given a subset S of the vertices in a graph, when all vertices in S connect to all other vertices in S, this is called a:


[x] clique

connected component

DAG

None of the above
2. A complete graph is a clique of size:


|E|

|n|

[x]|V|

None of the above
3. The number of edges incident to that vertex called its:


[x]degree

depth

count

number

None of the above
4. A graph containing all possible edges is a _____ graph


full

directed

dense

[x]complete
5. A digraph is a:


DAG

undirected graph

connected component

[x]directed graph


> You can refer to [link #2](#links) below for more info.

## Task 2

- Discuss how depth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/DFSAV.html


  //Depth-first search (DFS) is a popular graph traversal algorithm that can be used to explore all the nodes and edges of a graph.

When you run the DFS algorithm using the link provided, you can choose to create either a directed or an undirected graph. Then, you can choose a starting node and watch as the algorithm traverses the graph by visiting nodes in a depth-first manner.

In DFS, the algorithm starts at the selected starting node and explores as far as possible along each branch before backtracking. This means that it explores as deeply as possible before backtracking to explore other branches.

As the algorithm traverses the graph, it keeps track of which nodes it has already visited to avoid repeating them. When all nodes have been visited, the algorithm terminates.

Overall, DFS is a powerful algorithm that can be used to solve a variety of graph-related problems, such as finding a path between two nodes or detecting cycles in a graph. The visualization provided by the link can help you better understand how DFS works and how it can be used to traverse different types of graphs.








> You can refer to [link #3](#links) below for more info.

## Task 3

- Discuss how breadth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSAV.html

// Breadth-first search (BFS) is another popular graph traversal algorithm that can be used to explore all the nodes and edges of a graph.

When you run the BFS algorithm using the link provided, you can choose to create either a directed or an undirected graph. Then, you can choose a starting node and watch as the algorithm traverses the graph by visiting nodes in a breadth-first manner.

In BFS, the algorithm starts at the selected starting node and visits all its neighbors before moving on to the neighbors of those neighbors. This means that it explores all the nodes at a given depth before moving on to nodes at the next depth.

As the algorithm traverses the graph, it keeps track of which nodes it has already visited to avoid repeating them. When all nodes have been visited, the algorithm terminates.

Overall, BFS is another powerful algorithm that can be used to solve a variety of graph-related problems, such as finding the shortest path between two nodes or detecting connected components in a graph. The visualization provided by the link can help you better understand how BFS works and how it can be used to traverse different types of graphs.


> You can refer to [link #4](#links) below for more info.

## Task 4:

- Reproduce the behavior of the BFS algorithm for the following graph:
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSPE.html

Start at node A and mark it as visited.
Add A to the queue.
Dequeue A and visit its neighbors B and C. Mark B and C as visited and add them to the queue.
Dequeue B and visit its neighbor D. Mark D as visited and add it to the queue.
Dequeue C and visit its neighbor E. Mark E as visited and add it to the queue.
Dequeue D and visit its neighbor F. Mark F as visited and add it to the queue.
Dequeue E and visit its neighbor G. Mark G as visited and add it to the queue.
Dequeue F and visit its neighbor H. Mark H as visited and add it to the queue.
Dequeue G and there are no unvisited neighbors to visit.
Dequeue H and there are no unvisited neighbors to visit.
All nodes have been visited, so the algorithm terminates.
The order of visited nodes is: A, B, C, D, E, F, G, H.

> You can refer to [link #4](#links) below.

## Task 5: Individual (at home)

- There are two traditional approaches to representing graphs: The adjacency matrix and the adjacency list. What are the main differences in term of space/time complexity. You can refer to following link:
  https://www.baeldung.com/cs/adjacency-matrix-list-complexity

// The main difference between the adjacency matrix and the adjacency list in terms of space complexity is that the adjacency matrix uses O(V^2) space, where V is the number of vertices, while the adjacency list uses O(E+V) space, where E is the number of edges. This means that if the graph is sparse (i.e., has relatively few edges compared to vertices), the adjacency list may be more space-efficient.

In terms of time complexity, the adjacency matrix is faster for checking if there is an edge between two vertices, as it can be done in constant time O(1). However, the time complexity for iterating over all the neighbors of a vertex in the adjacency matrix is O(V), while in the adjacency list it is O(deg(v)), where deg(v) is the degree (i.e., the number of edges) of vertex v. This means that if we need to frequently iterate over the neighbors of vertices, the adjacency list may be more time-efficient.

Overall, the choice between the adjacency matrix and the adjacency list depends on the specific characteristics of the graph and the operations that need to be performed on it.

## Links

1. https://cpp.sh/
2. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphIntro.html
3. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#depth-first-search
4. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#breadth-first-search
