
# MATLAB Arrays and Matrices

MATLAB is an abbreviation for **MATrix LABoratory**. Most MATLAB functionality can work on multiple values at once.  
All MATLAB variables are arrays, meaning each numeric variable can contain multiple numbers. We can store related data in one variable using an array.

Arrays are a fundamental programming tool in MATLAB, and it's essential to understand their terminology:

- **Matrix**: A two-dimensional array.
- **Column vector**: An array with multiple rows and one column (n-by-1).
- **Row vector**: An array with one row and multiple columns (1-by-n).
- **Scalar**: A single number represented as a 1-by-1 array.

## MATLAB Tasks

### Task 1
Create a variable named `x` with a value of 4.

```matlab
x = 4;
```

### Task 2
Create an array named `y` with two elements: 7 and 9.

```matlab
y = [7 9];
```

### Task 3
Create an array named `z` with two elements, 7 and 9, in a single column.

```matlab
z = [7; 9];
```

### Task 4
Create a row vector named `a` that contains the values 3, 10, and 5 in that order.

```matlab
a = [3 10 5];
```

### Task 5
Create a column vector named `b` that contains the values 8, 2, and -4 in that order.

```matlab
b = [8; 2; -4];
```

### Task 6
Create a matrix named `c` with these values:

```
5    6    7
8    9   10
```

```matlab
c = [5 6 7; 8 9 10];
```

### Task 7
Create a row vector named `d` that contains `sqrt(10)` as the first element and `pi^2` (π²) as the second element.

```matlab
d = [sqrt(10) pi^2];
```

### Experimenting with Matrix Creation
Try experimenting with spaces, commas, and semicolons when creating this matrix:

```
7   1  8
4   5  8
10  4  2
```

```matlab
M = [7 1 8; 4 5 8; 10 4 2];
```

---

