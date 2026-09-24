# NumPy Arrays and Properties

This repository contains my practice and learning work on **NumPy Arrays** and their important properties in Python.

I started learning NumPy as part of my journey toward becoming an **AI Engineer**.

## What I Learned

### 1. Creating NumPy Arrays

I learned how to create arrays using `numpy.array()`.

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr)
```

### 2. Multidimensional Arrays

NumPy allows us to create arrays with multiple dimensions.

Example:

```python
arr = np.array([
    [[1, 2, 3, 4],
     [5, 6, 7, 8],
     [9, 10, 11, 12]],

    [[13, 14, 15, 16],
     [17, 18, 19, 20],
     [21, 22, 23, 24]]
])
```

This is a **3-dimensional array**.

Its shape is:

```text
(2, 3, 4)
```

Meaning:

* 2 → Number of blocks
* 3 → Rows in each block
* 4 → Columns/elements in each row

## NumPy Array Properties

I practiced the following important NumPy array properties:

### `ndim`

Returns the number of dimensions of an array.

```python
arr.ndim
```

Example:

```text
3
```

### `shape`

Returns the size of the array along each dimension.

```python
arr.shape
```

Example:

```text
(2, 3, 4)
```

### `size`

Returns the total number of elements in the array.

```python
arr.size
```

For an array with shape `(2, 3, 4)`:

```text
2 × 3 × 4 = 24
```

Therefore:

```text
arr.size = 24
```

### `dtype`

Returns the data type of the elements stored in the array.

```python
arr.dtype
```

Example:

```text
int64
```

## Example

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

print("Array:")
print(arr)

print("Dimensions:", arr.ndim)
print("Shape:", arr.shape)
print("Total Elements:", arr.size)
print("Data Type:", arr.dtype)
```

## Output

```text
Dimensions: 3
Shape: (2, 3, 4)
Total Elements: 24
Data Type: int64
```

## Key Concepts

| Property | Meaning                   |
| -------- | ------------------------- |
| `ndim`   | Number of dimensions      |
| `shape`  | Size along each dimension |
| `size`   | Total number of elements  |
| `dtype`  | Data type of elements     |

## Practice

I also practiced:

* Creating 1D arrays
* Creating 2D arrays
* Creating 3D arrays
* Understanding dimensions
* Understanding array shape
* Finding the total number of elements
* Checking data types
* Working with NumPy array properties

## Learning Goal

My goal is to build a strong foundation in NumPy before moving deeper into:

* Pandas
* Data Analysis
* Data Visualization
* Machine Learning
* Artificial Intelligence

## Learning Journey

**Python → NumPy → Pandas → Data Science → Machine Learning → AI Engineering**

---

### Author

**Zahid Khan**

BCA Graduate | Aspiring AI Engineer

Learning → Practicing → Building → Improving → Becoming an AI Engineer
