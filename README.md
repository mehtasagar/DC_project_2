# DC_project_2
This project simulates the Asynchronous BFS algorithm of distributed computing course.


## Project Description:
Simulate an asynchronous network using the simulator you developed in project 1.
The message transmission time for each link for each message is to be randomly chosen using uniform distribution in the range 1 to 18 “time units.” All links are bidirectional and FIFO. (FIFO: If process p sends two messages m1 and then m2 to process q, then process q receives m1 first and then m2.)
You will implement AsynchBFS with convergecast method for termination.
The code (algorithm) executed by all processes must be the same. [One process, the root of the BFS tree, knows about it being the root; all other processes don’t know the id of root of BFS till they receive a message.]
The input for this problem consists of the same input as that of project, with edge weights. You can ignore the edge weights for BFS where only connectivity is important. All links are bidirectional.
No process knows n. Each process knows the number of neighbors it has, the ids of its neighbors and the edge weights for the edges incident on them. Termination is to be done through the convergecast procedure.
Output the BFS by treating the tree as a graph and outputting the adjacency list.

### Team Project
