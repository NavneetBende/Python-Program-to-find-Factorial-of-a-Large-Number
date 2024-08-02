Factorial of a Large Number
On this page we will learn how to find the Factorial of a Large Number in python.

Factorial of a number is product of all the positive numbers less then and equals to the number we are finding factorial. On this page we will see two different ways to solve the Question one by inbuilt function and another by creating a function.

Input : 5
Output : 120
Explanation : 5! = 5 x 4 x 3 x 2 x 1 = 120
Factorial of a Large Number in Python
Method 1 : Without Inbuilt Function
Algorithm
Start
Pass the value of n to a function
Initialize a variable name answer with value one
Run a while loop until value of n is greater then 1
Multiply the value of n with ans and assign the result in ans
Decrement value of n by one
Return the value of answer
Python Program to Find Factorial of a Large Number
Python code
Run
def factorial(n):
    ans = 1
    while n > 1:
        ans *= n
        n -= 1

    return ans
n = 5
print(factorial(n))
Output
120
Related Pages
Find the “Kth” max and min element of an array 

Move all the negative elements to one side of the array

Find the Union and Intersection of the two sorted arrays

Find Largest sum contiguous Subarray

Minimize the maximum difference between heights 


Method 2 : Using Inbuilt Function for Factorial
Algorithm
From math library import Factorial Function
Assign to value to n for which you want to find Factorial
Pass the value of n to factorial function and assign the result to ans
Print ans
Python code
Run
from math import factorial

n = 5

ans = factorial(n)

print(ans)
Output
120
