Linked List Implementation
This repository contains an implementation of a linked list data structure in C#. The code provides a LinkedList class that allows for efficient insertion and searching operations.

Features
Node
The Node class represents a node in the linked list. It has properties for the value stored in the node and a reference to the next node.

Linked List
The LinkedList class represents a linked list data structure. It contains a head property that points to the first node in the list. Upon instantiation, an empty linked list is created.

The class provides the following methods:

Insert
Arguments: value
Returns: void
Adds a new node with the specified value to the head of the list with constant time complexity (O(1)).
Includes
Arguments: value
Returns: bool
Checks whether a node with the specified value exists in the linked list. Returns true if the value is found, false otherwise.
GetAllValues
Arguments: none
Returns: string
Returns a string representing all the values in the linked list, formatted as "{ value1 } -> { value2 } -> ... -> NULL".
Usage
To use the linked list implementation, follow these steps:

Instantiate a new instance of the LinkedList class.
Use the Insert method to add nodes to the linked list.
Use the Includes method to check if a value exists in the linked list.
Use the GetAllValues method to retrieve a formatted string representation of all the values in the linked list.
