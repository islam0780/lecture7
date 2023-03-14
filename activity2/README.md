# Activities

## Task 1

- Refer to the following link. Discuss the characteristics of Greedy approach:
  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/

//
The Greedy approach is a problem-solving strategy that works by making the locally optimal choice at each step. This means that at each step of the algorithm, the solution that appears to be the best is selected without considering the potential impact on future steps.

1. The characteristics of the Greedy approach are:

2. Greedy algorithms are easy to understand and implement.

3. They often provide simple and efficient solutions to problems.

4. Greedy algorithms typically have a lower time complexity than other algorithms, such as dynamic programming, which can make them a good choice for problems where efficiency is a concern.

5. However, greedy algorithms do not always provide the optimal solution. Because they make the locally optimal choice at each step, they may miss a better solution that requires making a suboptimal choice in the short term.

6. Greedy algorithms are particularly well-suited for problems where the problem space is well-structured and the optimal solution can be easily identified at each step.

Overall, the Greedy approach is a useful problem-solving strategy, particularly for problems where a simple and efficient solution is desirable. However, it is important to keep in mind that the solution provided by a Greedy algorithm may not always be the optimal solution, and other algorithms may be necessary to find the optimal solution in more complex problem spaces.

## Task 2

- Explain how the code in `./src/fkp.cp`p works. Refer to the following link:
  https://www.geeksforgeeks.org/fractional-knapsack-problem/

// The code solves the Fractional Knapsack Problem using a Greedy approach.

The Fractional Knapsack Problem is a classic optimization problem where we have a knapsack with a maximum weight capacity, and a set of items, each with a weight and a value. The goal is to determine the maximum value that can be packed into the knapsack, given its weight capacity.

The code works by sorting the items in descending order of their value-to-weight ratio. This is the key step in the Greedy approach, as it ensures that the algorithm selects the items that provide the maximum value for their weight at each step.

Then, the code iterates through the sorted items and selects as many of them as possible, starting with the item with the highest value-to-weight ratio. If an item cannot be fully packed into the knapsack, the algorithm adds a fractional amount of the item to the knapsack, based on the remaining capacity.

Finally, the code returns the total value of the items packed into the knapsack.

 the code provides a simple and efficient solution to the Fractional Knapsack Problem using a Greedy approach. However, it is important to keep in mind that the Greedy approach may not always provide the optimal solution for more complex problem spaces.

## Task 3

- Explain how the code in `./src/asp.cpp` works. Refer to the following link:
  https://www.geeksforgeeks.org/activity-selection-problem-greedy-algo-1/

// The code solves the Activity Selection Problem using a Greedy approach.

The Activity Selection Problem is a classic scheduling problem where we have a set of activities, each with a start time and a finish time, and the goal is to determine the maximum number of non-overlapping activities that can be scheduled.

The code works by sorting the activities in ascending order of their finish time. This is the key step in the Greedy approach, as it ensures that the algorithm selects the activities that finish earliest and leaves the maximum amount of time for the remaining activities.

Then, the code iterates through the sorted activities and selects the first activity that finishes earliest. For each subsequent activity, the algorithm checks if it overlaps with the previously selected activity. If it does not overlap, the algorithm selects the activity and updates the previously selected activity to the current one. If it overlaps, the algorithm discards the activity and moves on to the next one.

Finally, the code returns the number of selected activities, which represents the maximum number of non-overlapping activities that can be scheduled.

## Task 4: Individual (at home)

- Refer to te following link. Explain the differences between Greedy Algorithm and Dynamic Programming
  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/

  The main differences between Greedy Algorithm and Dynamic Programming are:

1. Approach: Greedy Algorithm is a problem-solving strategy that works by making the locally optimal choice at each step. Dynamic Programming is a problem-solving strategy that works by breaking down a complex problem into smaller subproblems, solving each subproblem once, and storing the solution to each subproblem to avoid redundant calculations.

2. Optimality: Greedy Algorithm typically does not provide the optimal solution to a problem, whereas Dynamic Programming guarantees an optimal solution.

3. Subproblems: Greedy Algorithm does not consider all possible subproblems or solutions, but rather focuses on the local optimal solution at each step. Dynamic Programming considers all possible subproblems and their solutions.

4. Efficiency: Greedy Algorithm is often more efficient than Dynamic Programming in terms of time complexity, but the solution it provides may not be optimal. Dynamic Programming may be less efficient than Greedy Algorithm in terms of time complexity, but it guarantees an optimal solution.

5. Complexity: Greedy Algorithm is often used for problems that have a greedy choice property, meaning that the locally optimal solution is also the globally optimal solution. Dynamic Programming is often used for problems that have optimal substructure, meaning that the optimal solution can be found by combining the optimal solutions to its subproblems.

Overall, the choice between Greedy Algorithm and Dynamic Programming depends on the problem at hand. If the problem has a greedy choice property and a simple greedy strategy can provide an acceptable solution, Greedy Algorithm may be a good choice due to its efficiency. However, if the problem is more complex and requires finding the optimal solution, Dynamic Programming may be a better choice despite its higher time complexity.

## Link(s)

- https://cpp.sh/
