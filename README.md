## 11 Data Structures Every Developer Should Know

source: https://blog.amigoscode.com/p/11-data-structures-every-developer?r=22x1kh&ref=dailydev&triedRedirect=true

If you're a software developer, data structures are your bread and butter. They're the fundamental building blocks of efficient algorithms and system design. Wether you're preparing for coding interviews, optimising your code, or working on complex applications, understanding how to use and implement data structures is essential.

In this blog post, we'll break down **11 data structures** that every dev should be familiar with. These structures are not only common in interviews but are also crucial for writing efficient and scalable code in real-world applications.

1. Array

An array is one of the most basic and commonly used data structures. It stores elements in a contiguous block of memory and allows for fast access via indices. Each element in an array is located at an index number, which provides firect access to retrieve or update an element.

**Use Case**: Arrays are ideal for storing list of elements that require constant-time access and modification. However, resizing arrays can be costly, and inserting or deleting elements from the middle of an array can be costly, and inserting or deleting elements from the middle of an array requires shifting elements.

**Example**: A list of numbers [48, 2, 79, 100, 88, 77] stored in an array allows you to quickly access any value using its index, such as array[2] to access 79.

2. 2D Array

A 2D array, also known as a matrix, in an array of arrays. It is used to represent data in a grid format, with rows and columns.

**Use Case**: Common applications of 2D arrays include representing images, game boards, and matrices in mathematical operations.

3. Queue

A queue is a First In, First Out (FIFO) data structure. In a queue, elements are inserted at the rear (back) and removed from the front. It's ideal for scenarios where you need to process tasks in the order they arrive.

**Use Case**: Queues are useful in scenarios like tasks scheduling, handling requests in servers, or breadth-first search in graphs.

**Example**: In a tasks scheduler, tasks are added to the back of the queue, and the scheduler processes them from the front.

4. Stack

A stack is a Last In, First Ou (LIFO) structure where elements are added and removed from the top. It's like a stack of books where you can only take from or add to the top.

**Use Case**: Stacks are used in scenarios such as undo operations in text editors, parsing expressions, or managing function calls (call stacks) in programming.

**Example**: When you hit "undo" in a text editor, the last action is removed from the stack of operations.

5. Graph

A graph consists of vertices (nodes) and edges (connections between the nodes). Graphs are used to represent relationships or networks where connections between entities are important.

**Use Case**: Graphs are widely used in networking, social media, and routing algorithms.
They are essential for problemas involving relationships, such as finding the sortest path between two points or modeling connections between people.

**Example**: A social network can be modeled as a graph, with users as nodes and friendships as edges.

6. Tree

A tree is a hierarchical structure consisting of nodes. Each node has a value and can have children nodes, forming branches.The topmost node is the root, and nodes without children are leaves.

**Use Case**: Trees are useful in representing hierarchical relationships such as file directories, organization charts, and more.

**Example**: A tree can represent a family hierarchy, with the root being the ancestor and branches leading to descendants.

7. Linked List

A linked list is a linear data structure where each element (called a node) contains a value and a reference (or pointer) to the next node in the sequence. Unlike arrays, linked lists do not require contiguous memory and can grow or shrink dynamically.

**Use Case**: Linked lists are useful for scenarios where you expect frequent insertions or deletions, especially in the middle of a list.

**Example**: Image a music playlist where you can add or remove songs dynamically, and each song is linked to the next.

8. Trie

A trie (pronounced "try") is a tree-like data structure used to store strings. It is often used in scenarios where efficient retrieval of a prefix or word ie needed, such as in search engines and dictionaries.

**Use Case**: Tries are useful for autocomplete systems or search suggestions, where you need to quickly find words with a common prefix.

**Example**: In an autocomplete feature, when a user types "cat," the trie can quickly suggest words like "catapult" or "catalog."

9. HashMap

A HashMap (or hash table) is a data structure that stores key-value pairs. It uses a hash function to compute an index into an array of buckets from which the desired value can be found.

**Use Case**: HashMaps are perfect for fast lookups by key, such as in caching, database indexing, or couting ocurrences of elements.

**Example**: Imagine storing a dictionary where words are the keys and their definitions are the values. A HashMap allows you to quickly find the definition of any word.

10. HashSet

A HashSet is a collection of unique elements. Like a HashMap, it uses a hash function to map elements to buckets, but only stores values, ensuring no duplicates are present.

**Use Case**: HashSets are great when you need to maintain a collection of distinct elements and ensure fast lookups to check if an item is present.

**Example**: A set of unique user IDs for an application could be stored in a HashSet to ensure that no duplicates exist.

11. Max Heap

A max heap is a special tree-based data structure where each parent node is greater than its children. The largest element is always at the root. Max heaps are commonly used in priority queues.

**Use Case**: Max heaps are ideal for scenarios where you need to maintain the largest (or highest-priority) element at the top, such as job scheduling systems or finding the kth largest element in a dataset.