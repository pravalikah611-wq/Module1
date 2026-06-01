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

# Read two integers
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

# Create complex number
z = complex(a, b)

# Display complex number and its parts
print("Complex number:", z)
print("Real part:", z.real)
print("Imaginary part:", z.imag)

<img width="1606" height="681" alt="image" src="https://github.com/user-attachments/assets/c4f6e154-42b8-4209-981e-0ab8b565b684" />



## Output
<img width="1606" height="681" alt="image" src="https://github.com/user-attachments/assets/f3b046df-c0f5-4df9-bfe5-8eadcca9c280" />


## Result
The program successfully reads two integers, forms a complex number, and displays the complex number along with its real and imaginary parts.
