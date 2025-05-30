# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a=int(input())
if(a%2==0):
    print("EVEN")
else:
    print("ODD")
```


## Output
![Screenshot 2025-05-17 134510](https://github.com/user-attachments/assets/4fb6cee1-ebb3-4b70-86b7-b197523a930b)


## Result
Thus the program executed successfully.


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
```
a = (0 == True)      
b = (False == False)
c = True + True     
d = False + 9        

print("a is", a)     
print("b is", b)     
print("c:", c)       
print("d:", d)       


```

## Output
![Screenshot 2025-05-17 135138](https://github.com/user-attachments/assets/231f98ec-1d03-4b80-8c65-a3e345e4fb2a)

## Result
Thus the program executed successfully.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
char1 = 'T'
char2 = 'a'
print(char1)
print(char2)

```

## Output
![Screenshot 2025-05-17 135508](https://github.com/user-attachments/assets/b45519d6-d453-4628-83fd-731bd96ae95e)


## Result
Thus the program executed successfully.
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
```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)

```

## Output
![Screenshot 2025-05-17 140142](https://github.com/user-attachments/assets/2202b898-16dc-4c11-85f2-7ce12b323d7b)


## Result
Thus the program executed successfully.

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=input()
print(men_stepped_on_the_moon)
```

## Output
![Screenshot 2025-05-17 140715](https://github.com/user-attachments/assets/b56807ef-958c-4109-af56-8cb1f7e9c572)


## Result
Thus the program executed successfully.
