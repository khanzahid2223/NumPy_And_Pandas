# NumPy Learning

This repository contains my **NumPy learning and practice** as part of my journey toward becoming an **AI Engineer**.

NumPy (Numerical Python) is a fundamental Python library used for **numerical computing, array operations, data processing, and scientific computing**.

## What is NumPy?

NumPy provides powerful data structures and functions for working with numerical data efficiently.

The main data structure in NumPy is the **NumPy array (`ndarray`)**.

## Topics Covered

* NumPy Installation and Import
* Creating NumPy Arrays
* 1D Arrays
* 2D Arrays
* 3D Arrays
* Array Dimensions
* Array Shape
* Number of Elements
* Data Types
* Array Properties
* Random Array Creation
* Array Indexing
* Array Slicing
* Array Operations
* Mathematical Operations
* Array Reshaping
* Array Iteration
* Practice Problems

## NumPy Array Properties

Some important properties of NumPy arrays:

| Property | Description                          |
| -------- | ------------------------------------ |
| `ndim`   | Returns the number of dimensions     |
| `shape`  | Returns the size of each dimension   |
| `size`   | Returns the total number of elements |
| `dtype`  | Returns the data type of elements    |

### Example

```python
import numpy as np

arr = np.array([
    [[1, 2, 3, 4],
     [5, 6, 7, 8],
     [9, 10, 11, 12]],

    [[13, 14, 15, 16],
     [17, 18, 19, 20],
     [21, 22, 23, 24]]
])

print("Dimensions:", arr.ndim)
print("Shape:", arr.shape)
print("Total Elements:", arr.size)
print("Data Type:", arr.dtype)
```

### Output

```text
Dimensions: 3
Shape: (2, 3, 4)
Total Elements: 24
Data Type: int64
```

## Random Array Creation

NumPy provides the `random` module for generating random numbers and arrays.

```python
import numpy as np

arr = np.random.randint(1, 100, size=(3, 4))

print(arr)
```

## Repository Structure

```text
NumPy/
│
├── Arrays/
├── Array_Properties/
├── Random_Arrays/
├── Indexing/
├── Slicing/
├── Array_Operations/
├── Reshaping/
└── Practice_Questions/
```

## Learning Goal

I am learning NumPy to build a strong foundation for:

* Data Science
* Machine Learning
* Artificial Intelligence
* Data Analysis
* AI Engineering

## My AI Engineering Journey

```text
Python
   ↓
NumPy
   ↓
Pandas
   ↓
Data Science
   ↓
Machine Learning
   ↓
Deep Learning
   ↓
Artificial Intelligence
   ↓
AI Engineering
```

## Progress

* [x] NumPy Basics
* [x] Creating Arrays
* [x] Array Properties
* [x] Random Array Creation
* [ ] Indexing and Slicing
* [ ] Array Operations
* [ ] Reshaping
* [ ] Advanced NumPy

## Author

**Zahid Khan**

BCA Graduate | Aspiring AI Engineer

**Learn → Practice → Build → Improve → Become an AI Engineer**
