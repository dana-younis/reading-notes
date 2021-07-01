# Linked Lists 
List is an interconnected series of Nodes.
In a linked list, the main distinguishing property is that each node refers to the next node in the connection.
* Linked List: A data structure with nodes connecting/pointing to the following node in the list.
* Singly: refers to the number of node references.
* Doubly: means that within the node there are two (double) references.
* Node: items/links living in a linked list.
* Next: The reference to the next node is found in this attribute.
* Head: is the first node in the linked list reference of the node type.
* Current : Currently is a type node reference to the node being examined

- Growing a linked list </br>
We do not need to assign a memory before creating the linked list or to copy it and re-create the linked list since we will not "run out of space" the manner with an assigned array. Rearrange our pointers is definitely necessary.
When using the linked list

Usually, a linked list is effective while adding and removing most components, but searching for and finding one single member may be quite sluggish.

- A foreach or loop we cannot utilize. The best technique to get at a crossing is by using a whilst() loop.
If we try to pass through a node that is null unintentionally, a NullReferenceException is raised and our application crashes / ends.
What is going on in an example, exactly:
Create head current. Head current creation.
We're creating a loop for a while.
To verify if the current node value is equivalent to the value we want.
If the current node does not include the value we want, we must shift the current to the next referred node.

# Traversal
For crossing a linked list and extracting the required data the next value is highly significant, since you cannot use for each or for each loop and must utilize the next value at each node to direct us to the next point of reference for each node.
The most effective approach to traverse a linked list is with the while() Loop, so we can verify whether each iteration does not have a Next Node in the list - if we try to cross it on null, then our application crashes with NullReferenceException
When you cross the linked list, the current variable tells us precisely where we are in the linked list and allows us to cross the whole line list

# Big O
The time it takes for a function, operation or algorithm to perform dependent on the number of components we give to it.
The space and time complexity of the method are defined by a host of various equations, most of which are O (called as simply O, or occasionally "ordre") and n (variable n where n is the input size) (think back to our our ten, thousands, or millions of numbers).
# Lists for all shapes and sizes
Lists with a single link are the most simple form of lists that are connected based only on the fact that they are just one way. We cross the list through a single track, starting at the head node and crossing from the root to the final node, which ends in an empty null.
# Linear data structures
There is an order and a sequence for how they are built and crossed.
Items must not be organized in order in non-linear data structures, which means that we can pass the data structures in a non-linear way.
Trees and charts are likewise non-linear data structures which we cross in various ways.
Like letters, integers, words or phrases, data structures require bytes of memory to represent them.

#  Print Out Nodes
It is somewhat similar to what we did for the Includes() function to print all nodes in the Linked List. This is because we use our current node and a certain loop to cross the current linked list.
- Anyway, what is a Linked List?
Structures of linear data One feature of linked lists is that they are linear data structures, meaning there is a sequence and order of how they are built.
- Linked list sections?
A linked list may be large or tiny, but the components it contains are actually very basic, regardless of their size.