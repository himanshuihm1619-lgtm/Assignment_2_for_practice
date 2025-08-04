# Assignment_2_for_practice

# Assignment 2: Control Structures in Python  

This assignment covers **Module 3: Control Structures in Python** and includes two tasks:  

---

## Task 1: Check if a Number is Even or Odd  

### Description:  
The program takes an integer input from the user and checks whether the number is **even** or **odd** using the modulus operator (`%`).  

### Code Snippet:  
```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print(number, 'is an even number.')
elif number % 2 != 0:
    print(number, 'is an odd number.')

Example Run:

Enter a number: 16
16 is an even number.

Enter a number: 3
3 is an odd number.




###  Task 2: Sum of Integers from 1 to 50 Using a Loop
**Description:
The program calculates the sum of integers from 1 to 50 using a for loop and prints the result.
###**

Code Snippet:
x = 0
for i in range(1, 51):
    x += i
print("The sum of numbers from 1 to 50 is: ", x)
Example Run:
The sum of numbers from 1 to 50 is: 1275

