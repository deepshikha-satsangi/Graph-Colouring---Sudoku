# Graph-Coloring---Sudoku
In this project, we have designed and implemented a Sudoku problem by studying the relationship between Sudoku and graph. 

Graph : A Graph is a mathematical representation of set of objects where some pair of objects are connected (linked) to each other. The objects are represented by vertices (nodes) and the links are called edges.

Graph Coloring :  Graph coloring is colouring vertices such that no two adjacent vertices share the same colour. 

Here we are using Greedy Coloring Approach 

Algorithm : 
The Idea is to assign colors one by one to different vertices, starting from the vertex 0. Before assigning a colour, check for safety by considering already assigned colour to the adjacent vertices. Check if the adjacent vertices have the same colour or not. If there is any colour that does not violet the conditions, mark the colour assignment as part of the solution.

Step 1 − Arrange the vertices of the graph in some order.

Step 2 − Choose the first vertex and color it with the first colour.

Step 3 − Choose the next vertex and color it with the lowest numbered color that has not been color on any vertices adjacent to it. If all the adjacent vertices are colored with this color, assign a new color to it. Repeat this step until all the vertices are colored. 


Sample Problem :
![image](https://user-images.githubusercontent.com/67851193/126615928-0c2ddf72-528a-46c9-8962-78b67af6994b.png)

Expected Solution :
![image](https://user-images.githubusercontent.com/67851193/126616069-e0f30f7e-2c7e-400a-9ea0-c5ea9f1d0337.png)
