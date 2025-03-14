
# MATLAB Plotting Tasks

## Interaction Setup
```matlab
% Load data file
sample = data(:,1);
density = data(:,2);
v1 = data(:,3);
v2 = data(:,4);
mass1 = density.*v1;
mass2 = density.*v2;
```

## Plot Vectors
You can plot two vectors of the same length against each other using the `plot` function.

```matlab
plot(x, y)
```

---

## Task 1  
Create a plot with `sample` on the x-axis and `mass1` on the y-axis.

```matlab
plot(sample, mass1)
```

![Output](https://github.com/kashikaga/matlab/blob/main/plot%201.png)


---

## Task 2  
Plot `mass2` (y-axis) against `sample` (x-axis). Use red (`r`) star (`*`) markers and no line in your plot.

```matlab
plot(sample, mass2, "r*")
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%201.png)
---

## Task 3  
Enter the `hold on` command.  

Then plot `mass1` (y-axis) against `sample` (x-axis) with black (`k`) square (`s`) markers and no line.

```matlab
hold on
plot(sample, mass1, "ks")
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%201.png)
---

## Task 4  
Enter the `hold off` command.

```matlab
hold off
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%201.png)
---

## Task 5  
Plot the vector `v1`.

```matlab
plot(v1)
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%203.png)
---

## Task 6  
Plot `v1` with a line width of 3.

```matlab
plot(v1, LineWidth=3)
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%204.png)
---

## Task 7  
Plot `v1` (y-axis) against `sample` (x-axis) with red (`r`) circle (`o`) markers and a solid line (`-`). Use a line width of 4.

```matlab
plot(sample, v1, "ro-", LineWidth=4)
```
![Output](https://github.com/kashikaga/matlab/blob/main/plot%205.png)
---
