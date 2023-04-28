# Reading-Notes
```This web site will include a summary information about different fields.```

+ ## Code 102 - Intro to Software Development
+ ## Code 201 - Foundations of Software Development
+ ## Code 301 - Intermediate Software Development
+ ## Code 401 - Advanced Software Development

## 1. Data Structures and Algorithms
```
(1) Recursion: it is a function that calls it self,it makes solution clearer and easier to understand. it summarize the code in a few lines and it breaks down the problem into two cases , base case and recursive case.
```
```
    -Base case: when function stop calling it self. it determine when the function should stop calling it self.
```
```
    -Recursive case: when function calls it self.
```

```(2) **Data Structure :** Data structures are specialized methods for arranging and storing data in computers so that actions on the stored data can be carried out more quickly. The use of data structures is widespread and varied in the domains of computer science and software engineering.
      
1.Compound data: data items that grouped togethor.

2.Big O notation: it is the way we measure how good a data  structure is doing a specifiec thing like adding new items, storing and searching.
```

 **There are multiple types of data structure:**
 ```
 1-Node: The atomic unit of linked list which contains value and pointer. 
 "Pointer":cinnect you to the next node in chain.

 2-Array: it is a continous block of cells in computer memory.

 3-Hash Table: it is an object which works as array but its memory locations dosn't have to be next to each other.it has a "Collision" problem which means that two keys could hash to the same memory location.

 4-Stack: it looks like an array but with a few additional features. we can add to the top of it by using push() and we can remove from the top of it by using pob().

5-Queue: it looks like an array but with a few additional features. we can add to the end of it by using .enqueue() and we can remove from the it of it by using .dequeue().
7.Graphs : Similar to linked list where you have nodes that pointing to each other and the pointer in it called edge.

6-Trees: Special kind of hierarchical graph in which data expands out in one direction . we can use it to represent a lot of things.
The first node in tree called "Root" which should has two nodes , left node must be lower than root and right node must be higher than root. 
```
## Discussion Questions: ##
     Answer 1:We must consider the operations we will do and the frequency of their execution while choosing the optimum data structure to address a certain challenge.
    Answer 2: By using functions like if statement to determine when to function should stop calling it self