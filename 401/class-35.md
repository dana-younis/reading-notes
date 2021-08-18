# Graphs

 A graph is a collection of vertices connected by line segments called edges.
 
 __Vertex__ - Also called a node. An object with 0 or more adjacent vertices
 __Edge__ - A connection between two nodes
 __Neighbor__ - An adjacent node, connected via an edge
 __Degree__ - The number of edges connected to a vertex

 ## Directed vs Undirected

 - In an __undirected graph__, each edge is undirected or bi-directional. The edges don't go in a specific direction in these graphs.

 - In a __directed graph__(Digraph), every edge is directed. Every node has a points to other nodes, but not necessarily the other way around. 

 ## Complete vs Connected vs Disconnected

 - A __complete graph__ is one where all the nodes are connected to all the other nodes. 

 - A __connected graph__ has nodes that all have at least one edge. A tree is a form of a connected graph

- In a __disconnected graph__, some of the vertices may not have edges

## Acyclic vs Cyclic

 - An __Acyclic graph__ is focused and devoid of cycles This implies that nodes can move around and not finish up back where they started. A directed acyclic graph, or DAG, is also referred to as a tree.
 - A __cyclic graph__ does have cycles, meaning it starts and ends at the same vertex

## Graph representation

 - An adjacency matrix is represented through a 2-dimensional array. The connected nodes are represented by 1s. 

 - A sparse graph has few connections and a dense graph has many connections

 - An adjacency list is the most common way to represent a graph, and it is a collection of the linked lists in an array

 - A weighted graph shows the nodes with numbers along the edges
  Weighted Graphs A weighted graph is a graph with numbers assigned to its edges. These numbers are called weights. When representing a weighted graph in a matrix, you set the element in the 2D array to represent the actual weight between the two paths. If there is not a connection between the two vertices, you can put a 0, although it is known for some people to put the infinity sign instead. Within adjacency lists, you must include both the weight and the name of the adjacent vertex. {vertices, weight}

 - Graphs are traversed like trees. Some graphs are cyclical, so you need to add a 'flag' to nodes that you already traversed

 - One way is breadth first. This uses a queue to help traverse. It basically looks at the first node, then nodes one edge away, then two, etc. This won't work if there are some node that can't be reached by the first node, and it won't work if there are some completely disconnected nodes. 

 - Depth first uses a stack to traverse. 
Depth First In a depth first traversal, we approach it a bit different than the way we do when working with a depth first traversal of a tree. Similar to how the breadth-first uses a queue, we are going to use a Stack for our depth-first traversal.

The algorithm for a depth first traversal is as follows:

Push the root node into the stack Start a while loop while the stack is not empty Peek at the top node in the stack If the top node has unvisited children, mark the top node as visited, and then Push any unvisited children back into the stack. If the top node does not have any unvisited children, Pop that node off the stack repeat until the stack is empty.
 - Graphs are very commonly used. They are used in GPS, driving directions, social networks, airline traffic, and Netflix uses them for recommendations. 

