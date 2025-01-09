For the “0. Island Perimeter” project, you will need to apply your knowledge of algorithms, data structures (specifically matrices or 2D lists), and iterative or conditional logic to solve a geometric problem within a grid context. The goal is to calculate the perimeter of a single island in a grid, where the grid is represented by a 2D array of integers. Understanding how to navigate and analyze 2D arrays and apply logical operations to determine the conditions for perimeter calculation is crucial for this task.

Concepts Needed:
2D Arrays (Matrices):

Accessing and iterating over elements in a 2D array.
Understanding how to navigate through adjacent cells (horizontally and vertically).
Conditional Logic:

Applying conditions to determine whether a cell contributes to the perimeter of the island.
Counting Techniques:

Developing a method to count the edges that contribute to the island’s perimeter.
Problem-Solving Strategies:

Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.
Python Programming:

Nested loops for iterating over grid cells.
Conditional statements to check the status of adjacent cells

Tasks
0. Island Perimeter
mandatory
Score: 0.0% (Checks completed: 0.0%)
Create a function def island_perimeter(grid): that returns the perimeter of the island described in grid:

grid is a list of list of integers:
0 represents water
1 represents land
Each cell is square, with a side length of 1
Cells are connected horizontally/vertically (not diagonally).
grid is rectangular, with its width and height not exceeding 100
The grid is completely surrounded by water
There is only one island (or nothing).
The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island)..
