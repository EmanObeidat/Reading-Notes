# Ten Thousand 2
**Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both**
```
Local scope:The area where a variable is defined within a function or a block of code. Only that specific function or block can access variables defined in the local scope. Outside of the function or block where they are defined, they cannot be accessed. Local variables are often used for calculations or temporary storage in a particular context and have a limited visibility.
```
```
Global scope refers to the region outside of any function or block of code. Variables defined in the global scope are accessible throughout the entire program. They can be referenced from any part of the code, including within functions or blocks. Global variables are often used for values that need to be shared across different functions or modules.
```
**How do the global and nonlocal keywords work in Python, and in what situations might you use them?**
```
 The global and nonlocal keywords are used to modify the scope of variables. They allow you to explicitly indicate whether a variable should be considered as a global variable or a nonlocal variable within a nested function.

 The global keyword is used to declare that a variable within a function should be treated as a global variable, even if there is a local variable with the same name. It enables you to modify and access a global variable from within a function.

 The nonlocal keyword is used to indicate that a variable within a nested function should be considered as a nonlocal variable, allowing you to modify a variable in the nearest enclosing scope that is not global.
 ```
 **In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.**
 ```
 The purpose of Big O notation in algorithm analysis is to provide a standardized and abstract way of comparing algorithms, focusing on their worst-case performance. It allows us to make informed decisions about which algorithm to use based on factors like execution time, memory usage, and computational resources.
 ```
 **Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python.**

 ```
 To simulate a dice roll using Python, you can use the random module, which provides functions for generating random numbers.
```
**Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials**
```
 To calculate the probability of rolling a specific number over a large number of trials, you would perform the following steps:

1)Set up a loop to simulate a large number of dice rolls.
2)Track the number of occurrences of the desired outcome (e.g., rolling a 6).
3)Divide the number of occurrences by the total number of trials to calculate the probability.
```