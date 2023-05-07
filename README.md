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
Developed by: VASUNDRA SRI R
RegisterNumber: 212222230168
def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
       smaller=n1
    else:
       smaller=n2
    for i in range(1,smaller+1):
        if (n1%i==0) and (n2%i==0):
           gcd=i
    print("GCD of two numbers is:",gcd)
    return gcd
```

## Output:


![gcd](https://user-images.githubusercontent.com/119393983/236669133-8b5bce48-6ff7-4b75-976b-66e857a7946e.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
