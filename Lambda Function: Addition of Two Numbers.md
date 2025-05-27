# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
~~~

sum_lambda = lambda a, b: a + b

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

result = sum_lambda(num1, num2)
print(f"\nThe sum of {num1} and {num2} is: {result}")
~~~

## Output
~~~
Enter the first number: 8
Enter the second number: 12

The sum of 8 and 12 is: 20
~~~

## Result
Thus given program is verified successfully.
