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
![square](https://github.com/Arun2005-create/Square-root-of-a-number/assets/138849356/abbf4c38-0b5c-43ce-be9b-be75e15aa082)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
