# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1:
Define a function.
### Step2:
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step3:
Set i = 0.
### Step4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step5:
Return number

## Program:
# Program to find the square root for the given number
# Developed by: THARUN D
# RegisterNumber: 23013993
~~~
n=int(input())
a=0.5*n
b=0.5*(a+n/a)
while b!=a:
    a=b
    b=0.5*(a+n/a)
print("Square root of the number:",a)
~~~
## Output:
![Screenshot 2023-12-21 210543](https://github.com/THARUNDT/Square-root-of-a-number/assets/144871537/c99d2572-894f-412f-996a-276bf3e8e2d2)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
