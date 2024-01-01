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
/*
Program to find the gcd of two number using function.
Developed by:Devesh s 
RegisterNumber:23004345  
*/
```
def gcd():

    m,n=int(input()),int(input())
    
    if m>n:
    
        smaller = n
        
    else:
    
        smaller = m
        
    for i in range(1,smaller+1):
    
        if(m%i==0 and n%i==0):
        
            result=i
            
    print("GCD of two numbers is:",result)        

## Output:

![Screenshot 2024-01-01 112957](https://github.com/23004345/GCD-of-two-numbers/assets/138849203/5349874a-d9c4-4bdd-a71e-5d1e7120ea1c)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
