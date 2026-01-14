# __`Numpy 101`__
Python’s foundational library for numerical computing.
___

__`Array`__ a data structure that contains a group of elements (values or variables) of the same size and data type (referred to as dytpes in NumPy). 

An array can be indexed by a tuple of nonnegative integers, by Booleans, by another array, or by integers.

__A Numpy two dimensional array__
```python
# Imports the NumPy library
In [1]: import numpy as np

# You pass a list of lists into np.array()
# NumPy interprets this as: 2 rows & 3 columns
# Because all elements are integers, NumPy chooses a single data type (int)
# Records the shape as (2, 3)
# 2D numerical array, not a nested Python list.
In [2]: arr = np.array([[0, 1, 2],
   ...:                 [3, 4, 5]])

In [3]: arr

Out[3]: 
array([[0, 1, 2],
       [3, 4, 5]])

* Dimensions(Rank): 2
* Shape: (2, 3)
* Total elements: 6
```
___
To select element 2, you first index the row and then the column.

___

```python
import numpy as np

arr = np.array([[0, 1, 2],
                [3, 4, 5]])

arr
```
___
```python
row 0:  0  1  2
row 1:  3  4  5
          ↑
        element 2
```


![Python logo](https://towardsdatascience.com/wp-content/uploads/2024/09/1T8BqVvPTcyuXbzWubPt8Zw.png)

__`array()`__ 

```python
In [8]: import numpy as np

In [9]: arr1d = np.array([1, 2, 3, 4])

In [10]: type(arr1d)

Out[10]: numpy.ndarray

In [11]: print(arr1d)
[1 2 3 4]
```
