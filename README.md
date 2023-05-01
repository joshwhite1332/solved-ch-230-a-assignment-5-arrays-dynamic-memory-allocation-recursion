Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-5-arrays-dynamic-memory-allocation-recursion
<br>
<h1>Problem 5.1 <em>Triangle chars                                                                                          </em></h1>

<h2></h2>

Write a function that takes two arguments: an integer n and a character ch. The function should print the character ch in a triangle form as below.

Write a simple program that reads the appropriate variables and prints the result to screen by calling the function.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 5.1: inputTestcase 5.1: output</h1>

4$$$$

$$$$

$$

$

<h2><strong>Problem 5.2 </strong>Divide with constant data</h2>

Write a function void divby5(float arr[], int size) that divides by 5 all elements of an array. Your program should print in the main() function the elements of the array before and after the division. Test your program with an array that contains the following values:

5<em>.</em>5<em>,</em>6<em>.</em>5<em>,</em>7<em>.</em>75<em>,</em>8<em>.</em>0<em>,</em>9<em>.</em>6<em>,</em>10<em>.</em>36.

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 5.2: inputTestcase 5.2: output</h1>

Before:

5.500 6.500 7.750 8.000 9.600 10.360 After:

1.100 1.300 1.550 1.600 1.9206 2.072

<h2><strong>Problem 5.3 </strong>Determine lowercase characters</h2>

Write a function int countlower(char* str) that counts the number of lowercase characters within in a string. Then write a program where you repeatedly read a string and determine and print the number of lowercase characters in that string. If you provide an empty string (the string will just contain ’
’), then the program should stop its execution. You must use a pointer to walk through the string.

<em>You can assume that the string will be not longer than </em>50 <em>characters and will be valid.</em>

<table width="414">

 <tbody>

  <tr>

   <td width="414"><strong>Problem 5.4 </strong><em>Divide with input data</em></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Modify your solution for <em>Divide I </em>such that you first read an integer n, and then elements of an array with n components. Therefore you will need to dynamically allocate your array. Then divide by 5 the elements using the divby5() function and print the result from the main() function. Do not forget to release the allocated memory when not needed anymore. <em>You can safely assume that the input will be valid.</em>

<h2><strong>Problem 5.5 </strong>Computing the scalar product of two vectors</h2>

Write a program that reads a number n, and then two vectors v and w of real numbers (of type double) with n components. Write a function that computes the scalar product of these two vectors. The scalar product is defined as:

n

v · w=<sup>X</sup>v<sub>i </sub>· w<sub>i</sub>

i=1

Use the function to compute the scalar product of the two vectors you read. From the main() function print the value of the scalar product on the screen. Additionally write functions for determining and printing on the screen the smallest and largest components of the vector v, and the position in the vector where they occur. <em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="564">

 <tbody>

  <tr>

   <td colspan="2" width="290"><strong>Testcase 5.5: input</strong></td>

   <td rowspan="2" width="274"><strong>Testcase 5.5: output</strong>Scalar product=6.600000The smallest = 1.100000Position of smallest = 0The largest = 3.000000Position of largest = 2The smallest = 1.000000Position of smallest = 0The largest = 1.000000Position of largest = 0</td>

  </tr>

  <tr>

   <td width="97">31.12.53.01.01.01.0</td>

   <td width="193"></td>

  </tr>

  <tr>

   <td width="97"><strong>Problem 5.6</strong></td>

   <td width="193"><em>Pointer arithmetic</em></td>

   <td width="274"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a program that counts the number of elements in an array until encountering the first negative value without the usage of any integer counter variables (except for the loop for reading the elements of the array), but with the usage of pointers and pointer arithmetic.

Your program should read an int for the length of the array and an array of floats (containing at least one negative value) from the standard input. The number of non-negative values before the first negative value should be printed on the standard output.

<em>You can assume that the input will be valid and the array will always contain at least one negative value. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="633">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 5.6: input</strong>5</td>

   <td width="343"><strong>Testcase 5.6: output</strong>Before the first negative value: 2 elements</td>

  </tr>

 </tbody>

</table>

1.2

3.4

-5.86

4

5.45

<h2><strong>Problem 5.7 </strong>Concatenating two strings</h2>

<h3>Language: C</h3>

Write a program to concatenate two strings (with the length of at most 100 characters) putting the result in a dynamically allocated array of chars with exact size.

Your program should read from the standard input two strings which may be statically allocated. The dynamically allocated string containing the concatenation result of the two strings should be printed on the standard output.

<table width="537">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 5.7: input</strong>one</td>

   <td width="247"><strong>Testcase 5.7: output</strong>Result of concatenation: onetwo</td>

  </tr>

 </tbody>

</table>

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones. </em>two

<h2><strong>Problem 5.8 </strong>Dynamically allocated matrix multiplication</h2>

Write a program that computes the multiplication of two dynamically allocated matrices.

Your program should dynamically allocate the memory for the three matrices (two input matrices and the result matrix). You should write functions for reading a matrix from the standard input, printing a matrix to the standard output, and finally a function for computing the multiplication of two matrices. At the end, do not forget to deallocate the memory used by the three matrices. The product of two matrices <em>A </em>and <em>B </em>of dimensions <em>n </em>× <em>m </em>and <em>m </em>× <em>p </em>can be calculated as:

<em>, </em>with <em>i </em>=1<em>,…,n </em>and <em>k </em>=1<em>,…,p.</em>

Your program should read three integers (the dimensions n, m and p) and the elements of two integer matrices from the standard input. The result of the matrix multiplication should be printed on the standard output.

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<h1>Testcase 5.8: inputTestcase 5.8: output</h1>

2Matrix A:

21 2

23 4

1Matrix B:

21 0

30 1

4The multiplication result AxB:

11 2

03 4

0

1

<h2><strong>Problem 5.9 </strong>Printing dynamically allocated 3D-array sections</h2>

Write a program that dynamically allocates memory for a 3D-array of integers and prints the 2Dsections parallel to the “<em>XOY </em>axis” (considering the array dimensions row-dimension, columndimension and depth-dimension similar to the geometrical <em>X</em>, <em>Y </em>and <em>Z </em>dimensions) of a 3Darray.

Your program should read three integer values corresponding to the dimensions of a 3D-array (in the order of rows, columns, depth) and should dynamically allocate the memory for this 3Darray. You should write functions for reading the elements of the 3D-array from standard input (first iterating through rows, then columns and then the depth) and finally a function for printing the 2D-sections of the 3D-array which are parallel to the “<em>XOY </em>axis”. Do not forget about the allocation and deallocation of the memory.

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<h1>Testcase 5.9: inputTestcase 5.9: output</h1>

2Section 1:

21 1

31 1

1Section 2:

22 2

32 2

1Section 3:

23 3

33 3

1

2

3

1

2

3

<h2><strong>Problem 5.10 </strong>Print numbers counting down</h2>

Write a program which reads a positive integer n from the keyboard. Then write and call a

recursive function for printing the numbers n<em>,</em>n − 1<em>,…,</em>1. <em>You can safely assume that the input will be valid.</em>

<h2><strong>Problem 5.11 </strong>Determine if a number prime</h2>

Write a program which reads a positive integer x. Then write a recursive function for determining if x is a prime number or not. The function should return 1 if the number is prime and 0 if not.

Print a corresponding message from the main() function.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<strong>Testcase 5.11: inputTestcase 5.11: output</strong>

2626 is not prime