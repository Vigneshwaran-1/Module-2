# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
# Python program to generate Pascal's Triangle
~~~
def generate_pascals_triangle(n):
    triangle = [[1] * (i + 1) for i in range(n)]
    
    for i in range(2, n):
        for j in range(1, i):
            triangle[i][j] = triangle[i - 1][j - 1] + triangle[i - 1][j]
    
    return triangle

num_rows = int(input("Enter the number of rows: "))

pascals_triangle = generate_pascals_triangle(num_rows)

print("\nPascal's Triangle:")
for row in pascals_triangle:
    print(" ".join(map(str, row)))
~~~
## Sample Output
~~~~
Enter the number of rows: 5

Pascal's Triangle:
1
1 1
1 2 1
1 3 3 1
1 4 6 4 1
~~~~

## Result
Thus given program is verified successfully.

