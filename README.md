# Find the square root of a number
## Date:
## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
Program to find the square root for the given number(newton's method) using function.
### Register Number: 212223230169
### Developed by: RAMYA R
```
def newton_square_root(b):
    if b<0:
        print("The Square root is not defined for negative number")
    x=b/2.0
    while True:
        new_x=0.5*(x+b/x)
        if new_x==x:
            break
        x=new_x
    return x
b=int(input())
result = newton_square_root(b)
print(f"Square root of the number: {result}")
```

## Output:
![alt text](<5 in.png>)
![alt text](<5 ot.png>)
## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
