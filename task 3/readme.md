Documentation:

A new node is created with the given data.

If the list is not empty:

The new node’s next pointer is set to the current head.
The current head’s prev pointer is updated to point to the new node.
Finally, the new node is made the new head of the list

1)Insert at the Beginning:

Create a new node with the given data.
If the list is empty, make the new node the head.
If the list has nodes, place the new node before the current head and update the pointers.

2)Insert at the End:

Create a new node and add it to the end of the list.
If the list is empty, the new node becomes the head.
If the list has nodes, traverse to the last node and link the new node after it.

3)Insert at a Specific Position:

Insert a new node at the given position.
If position == 0, it uses insert_at_beginning.
Otherwise, it traverses the list to find the right position and updates the pointers to insert the node.

Deletion Methods:

1)Delete from the Beginning:

Remove the first node (head) from the list.
If the list is empty, it raises an error.
If the list has only one node, it sets the head to None (empty list).

2)Delete from the End:

Remove the last node from the list.

3)Delete from a Specific Position:

Delete a node from a specific position.
It handles the case where the list is empty and raises an error if the position is out of bounds.
Adjusts the pointers of neighboring nodes after deletion.

