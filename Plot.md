
This code sets up the interaction.
load datafile
sample = data(:,1);
density = data(:,2);
v1 = data(:,3);
v2 = data(:,4);
mass1 = density.*v1;
mass2 = density.*v2;

Plot Vectors
You can plot two vectors of the same length against each other using the plot function.
plot(x,y)

Task 1
Create a plot with sample on the x-axis and mass1 on the y-axis.

You can specify the color, line style, and marker of a plot by using different symbols in double quotes as another input to the plot function.
plot(x,y,"r--o")
The command plots a red (r) dashed (--) line with circle (o) markers. You can learn more about the available symbols in the Line Specification documentation.

Task 2
Plot mass2 (y-axis) against sample (x-axis). Use red (r) star (*) markers and no line in your plot.

Notice that each plot command created a separate plot. You can plot one line on top of another in the same axes by using the hold on command.
plot(x1,y1)
hold on
plot(x2,y2)

Task 3
Enter the hold on command.

Then plot mass1 (y-axis) against sample (x-axis) with black (k) square (s) markers and no line.

While the hold state is on, plots continue to appear on the same axes. To return to the default plot behavior, where each plot appears on its own axes, enter hold off.

Task 4
Enter the hold off command.

When you plot a single vector by itself, MATLAB uses the vector values as the y-axis data and sets the x-axis data to the range of 1 to n (the number of elements in the vector).
plot(y)

Task 5
Plot the vector v1

When you use the plot function, you can optionally set properties using one or more name-value arguments, which consist of an argument name and an associated value. For example, this command plots a heavy line.
plot(y,LineWidth=5)
You can learn more about available properties in the Line Properties documentation.

Task 6
Plot v1 with a line width of 3

You can provide name-value arguments to the plot function after the line specification.
plot(x,y,"ro-",LineWidth=5)

Task 7
Plot v1 (y-axis) against sample (x-axis) with red (r) circle (o) markers and a solid line (-). Use a line width of 4
