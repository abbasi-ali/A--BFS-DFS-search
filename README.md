# A--BFS-DFS-search

In this project, I implemented all three of the A*, BFS, and DFS search algorithms in python. The end goal is to find the optimal solution in the snake game. 

The input is a .txt file which is structured as follows:

10,10

0,0

5 

3,4,2

2,2,1

9,1,1

5,7,2

4,9,1


the first line is the dimension of the world(10 * 10).
the second line is the starting point if the snake.
the third line is the numebr of the seeds that the snake is supposed to eat to grow:
there is a line for each seed: the first two elements show the coordinates of the seed and the last one shows the numebr of the seeds in that coordination. For example,
the forth line which is 3, 4, 2 shows that there are 2 seeds at (3, 4)

The optimal solution is printed as L, U, R, D, commands which are abvreviations for left, up, right, and down respectively. 

