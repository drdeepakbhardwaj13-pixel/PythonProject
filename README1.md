 Simple Python Calculator Program

This is a beginner-friendly Python program that performs **basic arithmetic operations** (addition, subtraction, multiplication, and division) between two numbers entered by the user.

---

 What the Program Does

1. Asks the user to input two numbers.
2. Converts the input strings to integers.
3. Performs:
   - Addition  
   - Subtraction  
   - Multiplication  
   - Division
4. Displays the results in a clean format.

---

 Code Example

```python
A = input("Enter the first number:")
B = input("Enter the second number:")
A = int(A)
B = int(B)

Addition = A + B
Subtraction = A - B
Multiplication = A * B
Division = A / B

print('Addition:', Addition)
print('Subtraction:', Subtraction)
print('Multiplication:', Multiplication)
print('Division:', Division)
