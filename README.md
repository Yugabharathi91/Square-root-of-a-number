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
# Developed by:YUGABHARATHI
# Register no:212224240314

def sqrt():
    b = int(input())
    x = b / 2
    for i in range(10):
        x = 0.5 * (x + b / x)
    print(f"Square root of the number: {x}")
sqrt()
```

## Output:
<img width="1112" height="371" alt="image" src="https://github.com/user-attachments/assets/0ddbdbbf-b6e4-497e-ba69-1a0e67a15b51" />



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
