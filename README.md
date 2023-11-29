# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function.
Developed by: Pavithra D
RegisterNumber: 23004871

def gcd():
    num1=int(input())
    num2=int(input())
    if num1>num2:
        min=num2
    else:
        min=num1
    for i in range(1,min+1):
        if(num1%i==0 and num2%i==0):
              gcd=i
    print("GCD of two numbers is:",gcd)

```

## Output:

![GCD 2](https://github.com/PavithraD23004871/GCD-of-two-numbers/assets/138955967/c2516a4e-9829-4ecb-9651-8228253f0f83)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
