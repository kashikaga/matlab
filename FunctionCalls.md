You can apply the size function to a vector or matrix to produce a single output variable containing the array size in a two-element row vector. The first element is the number of rows and the second element is the number of columns.
s = size(x)

Task 1
Create a variable named dsize containing the size of the data variable

You can also request two output variables from the size function. In this case, each variable contains the size of one of the dimensions of the input array. Use square brackets ([ ]) to request more than one output.
[xrow,xcol] = size(x)

Task 2
Create the variables dr and dc that respectively contain the number of rows and columns of the variable data.

You can find the maximum value of a vector and its corresponding index value using the max function. The first output from the max function is the maximum value of the input vector. When called with two outputs, the second output is the index value.
[xMax,idx] = max(x)

Task 3
Create the variables vMax and ivMax containing the maximum value of the v2 vector and the corresponding index value, respectively
