# Class05
## QUIZ

1. What is a linked list?

2. What are the advantages and disadvantages of using a linked list compared to an array?

3. What is the difference between a singly-linked list and a doubly-linked list?

4. What is a circular linked list?

5. What is a dummy node in a linked list?

6. What is a null pointer in a linked list?

7. How do you insert a new node into a linked list?

8. What is the time complexity of accessing an element in a singly-linked list, assuming the list has n elements?

9. What is the time complexity of inserting an element at the beginning of a singly-linked list?

10. What is the time complexity of inserting an element at the end of a singly-linked list?

11. What is the time complexity of deleting the last element in a singly-linked list? `(bouns qustion!)`


## Answers:

1. A linked list is a data structure in which elements are stored in nodes, and each node contains a reference to the next node.

2. The advantages of using a linked list are that it can dynamically resize, elements can be easily inserted or removed, and it uses memory more efficiently. The disadvantages are that it cannot be randomly accessed, traversal is slower than an array, and it requires extra memory to store the next pointers.

3. A singly-linked list has nodes that contain a reference to the next node, while a doubly-linked list has nodes that contain references to both the next and previous nodes.

4. A circular linked list is a linked list in which the last node has a reference to the first node, creating a loop.

5. A dummy node (also called a sentinel node) is a special node added to the beginning or end of a linked list to simplify certain operations.

6. A null pointer is a pointer that does not point to a valid memory location. In a linked list, a null pointer is used to indicate the end of the list.

7. To insert a new node into a linked list, you first create a new node with the data you want to insert, then update the next pointer of the new node to point to the node that comes after it, and update the next pointer of the previous node to point to the new node.

8. O(n)

9. O(1)

10. O(n)

11. O(n) `(bouns qustion!)`