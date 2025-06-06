# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
~~~

def find_modulo(a, b):
    return a % b

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

result = find_modulo(num1, num2)
print(f"\nModulo of {num1} % {num2} is: {result}")
~~~

## Output
~~~
Enter the first number: 17
Enter the second number: 5

Modulo of 17 % 5 is: 2
~~~

## Result
Thus given program is verified successfully.
