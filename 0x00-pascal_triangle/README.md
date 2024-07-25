What is Pascal's Triangle?
A pascal's triangle is an arrangement of numbers in a triangular array such that the numbers at the end of each row are 1 and the remaining numbers are the sum of the nearest two numbers in the above row.


Pascal's Triangle Formula
The formula to fill the number in the nth column and mth row of Pascal's triangle we use the Pascals triangle formula. The formula requires the knowledge of the elements in the (n-1)th row, and (m-1)th and nth columns. The elements of the nth row of Pascal's triangle are given by, nC0, nC1, nC2, ..., nCn. The formula for Pascal's triangle is:

nCm = n-1Cm-1 + n-1Cm

where

nCm represents the (m+1)th element in the nth row.
n is a non-negative integer, and
0 ≤ m ≤ n.

Must Know
To successfully complete this project, you should revise the following Python concepts:

Lists and List Comprehensions:

Understand how to create, access, modify, and iterate over lists.
Utilize list comprehensions for more concise and readable code, especially for generating rows of Pascal’s Triangle.
Functions:

Know how to define and call functions.
Pass parameters and return values, particularly how to return a list of lists representing Pascal’s Triangle.
Loops:

Use for and while loops to iterate through sequences.
Nested loops may be necessary for generating each row and calculating the values of Pascal’s Triangle.
Conditional Statements:

Apply if, elif, and else conditions to implement logic based on the position within Pascal’s Triangle (e.g., the edges of the triangle always being 1).
Recursion (Optional):

While not strictly necessary, understanding recursion can provide an alternative approach to generating Pascal’s Triangle.
Recognize base cases and recursive cases for a function that generates the triangle’s rows.
Arithmetic Operations:

Perform addition, a fundamental operation for calculating each element of Pascal’s Triangle as the sum of the two elements directly above it.
Indexing and Slicing:

Access elements and slices of lists, crucial for identifying and summing the correct elements when constructing each row of the triangle.
Memory Management:

Be mindful of how lists are stored and copied, especially when creating new rows based on the values of the previous row.
Error and Exception Handling (Optional):

Use try-except blocks as needed to handle potential errors, such as invalid input types or values.
Efficiency and Optimization:

Consider the time and space complexity of different approaches to generating Pascal’s Triangle.
Evaluate and apply optimizations to improve the performance of the solution.
