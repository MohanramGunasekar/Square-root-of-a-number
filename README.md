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
'''Program to find the square root for the given number(newton's method) using function.
Developed by: Mohanram Gunasekar
Register Number: 212223240095'''
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
```

## Output:
![Screenshot 2024-05-19 135728](https://github.com/MohanramGunasekar/Square-root-of-a-number/assets/139841812/91f82dde-5aa7-4dae-8af0-9b3f448ee41a)

![Screenshot 2024-05-19 135740](https://github.com/MohanramGunasekar/Square-root-of-a-number/assets/139841812/6e0f57f8-7a59-440f-8199-b1b3e23052fd)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
