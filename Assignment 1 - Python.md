Assignment - 1

Q1. Why do we call Python as a general purpose and high-level programming language?

Ans : Python is said to be a general purpose language because of the wise variety of use cases where python can be used. It is not specialized for any specific functions.

It is also a high level programming language as it is closer to human language and easy for humans to understand.

Q2. Why is Python called a dynamically typed language?

Ans : Dynamic typing means that the type of the variable is determined only during runtime and that is the case for Python. You don’t have to specify the type of variable defined in the program.

Q3. List some pros and cons of Python programming language?

Ans : 


|<h3>**Pros**</h3>|<h3>**Cons**</h3>|
| :-: | :-: |
|Beginner-friendly|Issues with design|
|Large Community|Slower than compiled languages|
|Flexible and Extensible|Security|
|Extensive Libraries|Work Environment|
|Embeddable|High memory consumption|
|Highly Scalable|Dynamically-typed language|
|IoT Opportunities|Complex multithreading|
|Portable|<p>Garbage collection leads to potential memory losses</p><p></p>|


Q4. In what all domains can we use Python?

Ans : Python can be used in almost all the domains where Computer science engineering can be applied.

This includes

1) Full stack App Development
1) IoT
1) Artificial Intelligence
1) Data Engineering / Data Science
1) Automation
1) Console Applications
1) Desktop Applications

Q5. What are variable and how can we declare them?

Ans : Variable can be said as containers with data values.

We can declare them like

```python:
a=7

str=’abc’
```

Q6. How can we take an input from the user in Python?

Ans : Syntax is

```python:
x=input("Enter anything.")
```
Q7. What is the default datatype of the value that has been taken as an input using input() function?

Ans : By default, input returns a string.

Q8. What is type casting?

Ans : As Python is a Dynamically Typed Language there may be times when you want to specify a type on to a variable. This can be done with casting.

Syntax is

```python: 
x = int(1) 
```

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Ans : Yes , we can do it with the help of split function. 

Syntax is

```python: 
x, y = input("Enter two values: ").split()
```

Q10. What are keywords?

Ans : Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.

Ans : No As the the keywords already define a specific purpose it would cause ambiguity and hence we can’t use Keywords as variables.

Q12. What is indentation? What's the use of indentaion in Python?

Ans : Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

Suppose you are inside a if statement, you need to put the indentation to specify you are inside the if block of code. It kind of works like Curly Braces in other programming languages.

Q13. How can we throw some output in Python?

Ans : We can use the Print Statement. 

Syntax :
```python:
print(“abc”) 
```

Q14. What are operators in Python?

Ans : Operators are used to perform operations on variables and values.

They include 

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Identity operators
- Membership operators
- Bitwise operators


Q15. What is difference between / and // operators?

Ans : / is used for Division and // is used for floor division.

Floor division will work like floor(x/y)

5//2 = 2 will be like floor(5/2)= floor(2.5) = 2

Q16. Write a code that gives following as an output.


iNeuroniNeuroniNeuroniNeuron


Ans : 

```python:
str=”iNeuron”

print(4\*str)

```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Ans :
```python:
` `x=input("Enter the number")

if ((int(x)%2) == 1):

`    `print("Odd")

else:

`    `print("Even")
```

Q18. What are boolean operator?

Ans : The Python Boolean type is one of Python’s built-in data types. It’s used to represent the truth value of an expression

Syntax : bool\_val = True


Q19. What will the output of the following?



1 or 0

0 and 0

True and False and True

1 or 0 or 0



Ans : 

i) True

ii) False

ii) False

ii) True

Q20. What are conditional statements in Python?

Ans : Conditional Block is used to determine whether a block of code will be executed or not.

Eg. If else statement

Q21. What is use of 'if', 'elif' and 'else' keywords?

Ans : 

If ,elif and else statements are used in conditional statements in python. 

If is used to declare the if-else statement. If the condition is satisfied the block gets executed.

Elif block gets executed if the if statement condition is not valid and elif statement condition is valid.

Finally else condition gets executed when none of the if or elif statement gets executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Ans : 

```python:
x=input("Enter age")

if int(x)>=18:

`    `print(" I can vote")

else:

`    `print(" I can't vote")

```
Q23. Write a code that displays the sum of all the even numbers from the given list.


numbers = [12, 75, 150, 180, 145, 525, 50]


Ans : 

```python:
numbers = [12, 75, 150, 180, 145, 525, 50]



for x in range(len(numbers)):

`    `print(numbers[x])
```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

```python:
num1 = input()

num2 = input()

num3 = input()

if (num1 >= num2) and (num1 >= num3):

`   `largest = num1

elif (num2 >= num1) and (num2 >= num3):

`   `largest = num2

else:

`   `largest = num3

print("The largest number is", largest)

```
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

\- The number must be divisible by five

\- If the number is greater than 150, then skip it and move to the next number

\- If the number is greater than 500, then stop the loop



numbers = [12, 75, 150, 180, 145, 525, 50]

Ans : 

```python:
numbers = [12, 75, 150, 180, 145, 525, 50]



for x in range(len(numbers)):



`        `if  numbers[x]>500:

`            `break

`        `elif numbers[x]>150:

`            `continue

`        `elif numbers[x]%5==0:

`            `print(numbers[x])

```























