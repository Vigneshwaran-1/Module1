
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
~~~
a = True
b = False

print("Boolean Expressions:")
print(f"True AND False: {a and b}")
print(f"True OR False: {a or b}")
print(f"NOT True: {not a}")
print(f"NOT False: {not b}")

print("\nArithmetic Expressions:")
print(f"True + True = {True + True}")
print(f"True + False = {True + False}")
print(f"False + False = {False + False}")
print(f"True * 5 = {True * 5}")
print(f"False * 10 = {False * 10}")
print(f"True - False = {True - False}")

print("\nMixed Expressions:")
print(f"(True + False) * 3 = {(True + False) * 3}")
print(f"(True * 2) + (False * 5) = {(True * 2) + (False * 5)}")
~~~

## Output
~~~
Boolean Expressions:
True AND False: False
True OR False: True
NOT True: False
NOT False: True

Arithmetic Expressions:
True + True = 2
True + False = 1
False + False = 0
True * 5 = 5
False * 10 = 0
True - False = 1

Mixed Expressions:
(True + False) * 3 = 3
(True * 2) + (False * 5) = 2
~~~
## Result
Thus program is verified successfully
