# File IO & Exceptions
**What is the purpose of the ‘with’ statement when opening a file in Python?**
```
The 'with' statement in Python is used when working with unmanaged resources, such as files.It is primarily used to ensure that a resource is properly managed and cleaned up after it has been used.
```
**how does it help manage resources while reading and writing files?**
```
it is automatically handles closing the file once the block of code inside the 'with' statement has completed, It eliminates the need for you to explicitly close the file, reducing the chance of resource leaks and data corruption.
 In summary, When using 'with' to read or write to a file, the 'with' statement ensures that the file is automatically closed when the block of code inside the 'with' statement is exited
```

**Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python.**
```
The main difference between these methods is how they read the data from the file.

read():it reads the entire content of a file and returns it as a single string. If we do not specify the number of characters to read, the entire file is read. "read all file togethor"

readline() method reads a single line of text from a file and returns it as a string. Each time readline() is called, the next line of the file is read ."read line by line"
```
 *Provide examples of when to use each method.*
 ```
 If you need to read the entire contents of a file, use read(). If you need to read a file line-by-line, use readline()
 ```
 ## ‘try’, ‘except’, and ‘finally’
 
 $\colorbox{red}{These are used in Python to handle exceptions and ensure proper execution of code.}$
```
'try' :The code that can cause an exception is found in the try block. If an exception is thrown, the try block's execution is terminated and control is transferred to the closest except block that matches the exception.

'except': The code that manages exceptions is found in the except block. It must identify the kind of exception it is catching and may also include an optional variable to hold the exception's data.

'finally': Regardless of whether an exception was raised or not, the code in the finally block will always be carried out. This block is generally employed for cleanup operations like resource release or file closure.
```
In summary: The try block contains the code that may raise an exception, the except block contains the code that handles the exception, and the finally block contains code that is guaranteed to be executed, whether an exception was raised or not.