
# MATLAB Array Size and Maximum Value Extraction

This script demonstrates how to determine the size of a matrix, extract the number of rows and columns, and find the maximum value of a vector along with its index.

## Tasks

### Task 1: Determine the Size of a Matrix
Create a variable `dsize` that stores the size of the `data` variable.

```matlab
dsize = size(data);
```

### Task 2: Extract Number of Rows and Columns
Create the variables `dr` and `dc` that store the number of rows and columns of the `data` variable, respectively.

```matlab
[dr, dc] = size(data);
```

### Task 3: Find Maximum Value and Its Index
Create the variables `vMax` and `ivMax` that store the maximum value of the `v2` vector and its corresponding index.

```matlab
[vMax, ivMax] = max(v2);
```

## Usage
- Ensure that the `data` variable is defined as a matrix before executing the script.
- The `v2` variable should be a vector for the `max` function to return meaningful results.

This script is useful for basic matrix operations in MATLAB, especially for analyzing dataset dimensions and extracting key values.
