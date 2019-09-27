# Micro and Array Update

   Micro purchased an array A having N integer values. After playing it for a while, he got
bored of it and decided to update value of its element. In one second he can increase
value of each array element by 1. He wants each array element's value to become greater
than or equal to K. Please help Micro to find out the minimum amount of time it will take,
for him to do so.

<h1>Input:</h1>
First line consists of a single integer, T, denoting the number of test cases.
First line of each test case consists of two space separated integers denoting N and K.
Second line of each test case consists of N space separated integers denoting the array
A.

<h2>Output:</h2>
For each test case, print the minimum time in which all array elements will become
greater than or equal to K. Print a new line after each test case.

<h3>Constraits:</h3>

1<=T<=5


1<=N<=10^5


1<=A[i],k<=10^6

<h4>Sample Input:</h4>

2


3 4


1 2 5


3 2


2 5 5

<h5>Sample Output:</h5>

3


0


# Hamiltonian and Lagrangian
  Students have become secret admirers of SEGP. They find the course exciting and the
professors amusing. After a superb Mid Semester examination, it’s now time for the
results. The TAs have released the marks of students in the form of an array, where arr[i]
represents the marks of the ith student.

Since you are a curious kid, you want to find all the marks that are not smaller than those
on its right side in the array.

# Input Format
 The first line of input will contain a single integer n denoting the number of students.
The next line will contain n space separated integers representing the marks of students.

# Output Format
Output all the integers separated in the array from left to right that are not smaller than
those on its right side.

# Constraints

 1 <= n <= 1000000
 
 0 <= arr[i] <= 10000
 
 # Sample Input 
 
 6
 
 16 17 4 3 5 2
 
 # Sample Output
 
 17 5 2
