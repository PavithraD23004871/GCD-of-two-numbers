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

num=int(input())
a=1e-6
max=100

guess=num/2.0
for _ in range(max):
    new=0.5*(guess+num/guess)
    if abs(new-guess)<a:
       break
    guess=new
print(f"Square root of the number: {new}")

```

## Output:
![Alt text](GCD.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
