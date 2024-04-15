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
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
#Register Number: 212223230169
#Developed by: RAMYA R
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
![Screenshot 2024-04-15 134632](https://github.com/ramya23000505/Square-root-of-a-number/assets/149370791/474844bc-fe84-44fd-b2df-c499d64e1319)
![Screenshot 2024-04-15 134640](https://github.com/ramya23000505/Square-root-of-a-number/assets/149370791/1ec7e6d0-1f20-4538-9b21-d113bcfb7fc0)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
