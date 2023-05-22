## What is the purpose of dunder methods in Python?
```
Dunder methods, commonly referred to as magic methods or special methods, are predefined methods that offer a mechanism to create particular behaviors for objects in a class. When certain language-specific activities or events, such as object initialization, attribute access, comparison, or arithmetic operations, occur, these methods are automatically invoked.
```

### Provide an example of a commonly used dunder method.
```
One commonly used dunder method is __init__(), which is used to initialize an object when it is created
```
### Describe the Python statistics module :
```
The built-in Python statistics module, which was first made available in version 3.4, offers functions for interacting with statistical data. It provides a wide range of statistical operations, such as correlation coefficients, measures of central tendency, and measures of dispersion.
```
### give an example of a function within the module that can be used to perform a common statistical operation
```
import statistics

data = [1, 2, 3, 4, 5, 6]

mean_value = statistics.mean(data) "calculates the mean (average) of the data"
print("Mean:", mean_value)

median_value = statistics.median(data) "calculates the median (middle value) of the data"
print("Median:", median_value)

mode_value = statistics.mode(data) 
" calculates the mode (most common value) of the data. Note that if there are multiple modes or no mode exists, it will raise a statistics.StatisticsError."

print("Mode:", mode_value)

stdev_value = statistics.stdev(data)
"calculates the standard deviation of the data, which measures the spread or dispersion of the values."
print("Standard Deviation:", stdev_value)

```