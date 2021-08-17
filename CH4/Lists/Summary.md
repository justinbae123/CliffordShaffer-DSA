# List 
- **DEF'N**: finite, ordered sequence of data items known as "elements"
- Position : List must have a position(ordered) / analogous to the mathematical concept of 'sequence'

## List Features
- Empty : It contains no elements
- Length : The number of elements currently stored in the list
- Head : The beginning of the list
- Tail : The end of the list
- Sorted list : Elements are positioned in ascending order of value
- Unsorted list : Elements have no particular relationship

## Advantage of the list DS
- There are operations such as insert and delete which works at the current position
  - This will make adding and deleting an element much easier and faster

## Implementation
- Array-based List
  - It actually uses [] operator from c array, so traversing over the elements is easy
  - Just looking apparently, cannot find out any difference with c++ vector(maybe there will be differnece when inserting an element)
- Linked List
  - Linked list is made up of a series of objects called the nodes(node is a distinct object opposed to a cell in an array)
  - Basically, considering encapsulation, node should be the private member of the linked list
