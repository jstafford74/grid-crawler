# grid-crawler

## Problem:
    Create a simple single page application that can find the shortest path
    on a grid given a starting point, an ending point and an unlimited amount
    of obstacles.
 
## Solution:
    I applied the Breadth-First Search (BFS) algorithm to solve this problem.
    
    The BFS algorithm uses a queue data structure(array in javascript) to create an
    accessible memory of which cells have been visited, are blocked or are valid.
    Once the queue finds the goal, or endpoint, the shortest path has been obtained.

    The reason the BFS algorithm can find the shortest path is because the grid is
    being explored in each direction at equal speeds. The quickest return with the goal
    is the shortest path.  In this application of the BFS algorithm, I allowed the search
    to go in every direction, including the diagonals.

    In order to match the results of the algorithm to the rendering of the web page,
    there are 2 grids constructed: a calculation grid & a DOM grid.  Each cell contains
    a value attribute that represents the location on the grid.  Once the algorthm finds the 
    endpoint, the class of each cell along the shortest route is changed to represent the 
    color of the pathway.

    This project is constructed using Html5, Bootstrap, Javascript, jQuery & Font-Awesome.
