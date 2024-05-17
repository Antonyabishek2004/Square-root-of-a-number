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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Antony Abishek K
RegisterNumber: 212223240009
*/
def newton_square_root(number):
    if number<0:
        print("Square root is not defined for negative numbers.")
    x=number/2.0
    while True:
        new_x=0.5*(x+number/x)
        if new_x==x:
            break
        x=new_x
    return x
number=int(input())
result=newton_square_root(number)
print(f"Square root of the number: {result}")

```
## Output:
![Screenshot 2024-05-17 231416](https://github.com/Antonyabishek2004/Square-root-of-a-number/assets/138849620/53c5ce1d-7f65-4af9-adf8-7d2113b4a199)
![Screenshot 2024-05-17 231429](https://github.com/Antonyabishek2004/Square-root-of-a-number/assets/138849620/33f87fcb-2417-4984-8171-18c5f31fde96)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
