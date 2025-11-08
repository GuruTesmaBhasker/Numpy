# Numpy
# NumPy Learning Summary

This document lists the NumPy concepts I have learned and practiced.


## NumPy Basics

- What NumPy is and why it is faster than Python lists  
  (vectorization, contiguous memory, operations written in C)
- ndarray: NumPy's main array object



## Creating Arrays

| Function | Purpose |
|----------|----------|
| `np.array()` | Convert list/tuple into a NumPy array |
| `np.zeros()` | Create array filled with 0 |
| `np.ones()` | Create array filled with 1 |
| `np.full()` | Create array filled with a specific value |
| `np.empty()` | Create an uninitialized array |
| `np.arange()` | Create array using range (step-based) |
| `np.linspace()` | Create evenly spaced numbers between a range |
| `np.logspace()` | Create numbers evenly spaced on a log scale |
| `np.random.rand()` | Random floats (0 to 1) — Uniform distribution |
| `np.random.randn()` | Random floats — Normal distribution |
| `np.random.randint()` | Random integers in range |



## Array Information and Properties

| Attribute | Description |
|----------|-------------|
| `ndim` | number of dimensions (1D / 2D / 3D) |
| `shape` | structure (rows, columns…) |
| `size` | total elements in the array |
| `dtype` | data type of array elements |
| `itemsize` | memory used per element |



## Indexing & Slicing

- Accessing elements using `arr[i]`
- Slicing: `arr[start:end]`
- 2D indexing: `arr[row, col]`
- Boolean indexing: `arr[arr > 5]`
- Fancy indexing: `arr[[0, 2, 4]]`



## Array Operations

- Element-wise addition, subtraction, multiplication, division
- Comparison operations
- Broadcasting: operations between different-shaped arrays



## Data type handling

- Integer (`int`) vs Unsigned integer (`uint`)
- `astype()` → convert data type
- `string_` and `unicode_` text types



##  Reshaping and Transpose

| Operation | Meaning |
|-----------|---------|
| `reshape()` | Change array shape without changing data |
| `ravel()` / `flatten()` | Convert 2D/3D array into 1D |
| `transpose()` / `T` | Swap rows and columns |



##  Searching & Filtering

| Function | Purpose |
|----------|----------|
| `np.nonzero()` | Returns indices of non-zero elements |
| Boolean mask | Extract values based on condition |



### Summary

Now I can:

- Create arrays
- Analyze array structure
- Perform vectorized operations
- Use broadcasting
- Filter, slice, reshape, and manipulate data

These concepts form the foundation for **Pandas and Data Analysis**.

