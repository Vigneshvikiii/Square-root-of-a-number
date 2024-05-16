# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.~~
5. Return number

## Program:
~~~
Program to find the square root for the given number(newton's method) using function.
Developed by: Vignesh S
RegisterNumber:  212223230240
def sqr(number):
   a = number/2.0
   while True:
       new = 0.5*(a+number/a)
       if abs(new-a)<1e-10:
           return new
       a=new
input_num = float(input())
result = sqr(input_num)
print("Square root of the number:",result)

~~~


## Output:

![image](https://github.com/Vigneshvikiii/Square-root-of-a-number/assets/147474483/f12079d8-0159-44ce-b964-bc32b717bded)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
