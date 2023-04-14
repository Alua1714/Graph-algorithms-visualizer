# Graph-algorithms-visualizer
An interface implemented in Js, HTML and Css that allows the user to visualize any pathfinding algorithm on a graph. 
Note that the program is not polished and needs some last visual modifications. However it works perfectly fine and can be tested.
To make the program work just execute it in a local host.
An interface witha  grid and two inputs should apear. There should be four buttons. The grid nodes are numbered from starting at 1 at top-left corner and finishing at bottom right corner going in columns. 
"1,2,3..... n-1, n"
"n+1, n+2......., 2n"
....................
".................n*n"

To run a BFS just type the nodes Id in the input and click "run BFS"
To run a Dijkstra click "generate random weights" which generated the weighted graph randomly, select the starting and ending nodes and click "run dijkstra"
The last button generated a random maze with a randomized DFS. To use it click the button, wait for the generation to complete and then select starting and ending nodes and click "run BFS" to solve the maze.


It is possible that after an algorithm is completed it bugs and does not work anymore just reset the page and it should work again. Remember that thsi is a prototype made for fun.
