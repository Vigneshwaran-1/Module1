# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
~~~
real_part = int(input("Enter the real part: "))
imaginary_part = int(input("Enter the imaginary part: "))

complex_number = complex(real_part, imaginary_part)

print(f"\nComplex Number: {complex_number}")
print(f"Real Part: {complex_number.real}")
print(f"Imaginary Part: {complex_number.imag}")
~~~
## Output
~~~
Enter the real part: 4
Enter the imaginary part: 7

Complex Number: (4+7j)
Real Part: 4.0
Imaginary Part: 7.0
~~~



## Result
Thus program is verified successfully.
