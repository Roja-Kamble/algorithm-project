# algorithm-project

**Knight tour problem**

Statement: Given a N*N board with the Knight placed on the first block of an empty board. Moving according to the rules of chess knight must visit each square exactly once. Printing the result in the order of each cell knight is visited using backtracking algorithm.

Constraints:
Knight visit each cell only once
Knight should be wothin boundaries of the board
Knight follows a close tour

Team size: 2
Team members: Roja Kamble, Meenasree Ananthavelu

**Open/Close tour**

Close tour => A knight's tour is said to be closed if the last square visited is also reachable from the first square by a single knight's move.

Open tour => A knight's tour in which every square on the board is visited exactly once but without being able to return to the origin in one move is called an open knight's tour.

**Backtracking algorithm**

Backtracking algorithm: Backtracking is an algorithmic that tries different solutions until finds a solution that “works”. This technique has a property to solve the problem. 

Property: These problems can only be solved by trying every possible configuration and each configuration is tried only once.

Naïve solution: A naive approach is to attempt all configurations and produce a configuration that satisfies to the problem requirements.

Backtracking works incrementally and is an improvement over the Naive solution, tests all potential configurations generated.

**How to run the project**

**Time complexity**

Time complexity is O(N^2) as you can see in the middle position it does follow the O(N^2) curve closely, whereas, for the start position of (0,0) since we do not have enough data set to visualize the full curve, it loosely follows O(N^2) curve.

**Data sets for experiment**

**Goals**

**Results**

