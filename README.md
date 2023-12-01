# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1
1. Define a function.
## Step2
2. Assign number_iters = 100 in the function to perform 100 iteratios.
## Step3
3. Set i = 0.
## Step4
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## Step5
5. Return number

## Program:
```
#Program name :Square root of the number
#Developed by :Arun kumar B
#Register number:23004514
def newton_method(number,number_iters = 100):
    a = float(number)
    for i in range(number_iters):
        number = 0.5 *(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![output](/square.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
