MATLAB is an abbreviation for MATrix LABoratory. Most MATLAB functionality can work on multiple values at once.
All MATLAB variables are arrays. So,each numeric varialbe can contain multiple numbers. We can store related data in one variable by using an array.
Arrays are a basic programming tool in the MATLAB language, it's important to get to know them and the terminology used to describe them.
Matrix 
Column vector 
Scalar
Row vector

In MATLAB, a single number, called a scalar, is represented by a 1-by-1 array, meaning the array contains one row and one column.
Task 1
Create a variable named x with a value of 4.

You can create arrays with multiple elements using square brackets.
x = [3 5]
x = 
    3    5
Task 2
Create an array named y with two elements: 7 and 9

When you separate numbers by using spaces as shown in the previous task, MATLAB combines the numbers into a row vector, which is an array with one row and multiple columns (1-by-n). When you separate numbers by using semicolons, MATLAB creates a column vector (n-by-1).
x = [1;3]
x = 
    1
    3
Task 3
Create an array named z with two elements, 7 and 9, in a single column.

Try copying the previous command and changing the space between the numbers to a semicolon (;)

Task 4
Create a row vector named a that contains the values 3, 10, and 5 in that order

Task 5
Create a column vector named b that contains the values 8, 2, and -4 in that order.

You can use a combination of spaces and semicolons to create a matrix, which is an array with multiple rows and columns. When creating a matrix, you enter the elements row by row.
x = [3 4 5; 6 7 8]
x = 
    3    4    5
    6    7    8
Task 6
Create a matrix named c with these values.
5    6    7
8    9   10

You can perform calculations within the square brackets.
x = [abs(-4) 4^2]
x = 
     4    16
Task 7
Create a row vector named d that contains sqrt(10) as the first element and pi^2 (π^2) as the second element.

Try experimenting with spaces, commas, and semicolons when creating this matrix.

7  1 8
4  5 8
10 4 2

