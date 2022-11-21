Python Mega Assignment

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
 x=input("Enter the number")

if ((int(x)%2) == 1):

    print("Odd")

else:

    print("Even")
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

    print(" I can vote")

else:

    print(" I can't vote")

```
Q23. Write a code that displays the sum of all the even numbers from the given list.


numbers = [12, 75, 150, 180, 145, 525, 50]


Ans : 

```python:
numbers = [12, 75, 150, 180, 145, 525, 50]



for x in range(len(numbers)):

    print(numbers[x])
```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

```python:
num1 = input()

num2 = input()

num3 = input()

if (num1 >= num2) and (num1 >= num3):

   largest = num1

elif (num2 >= num1) and (num2 >= num3):

   largest = num2

else:

   largest = num3

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



        if  numbers[x]>500:

            break

        elif numbers[x]>150:

            continue

        elif numbers[x]%5==0:

            print(numbers[x])

```

Q26. What is a string? How can we declare string in Python?

Ans: Strings in Python are arrays of bytes representing unicode characters.

Syntax:
```python:
Name="Sidharth"
```

Q27. How can we access the string using its index?

Ans:
```python:
Name="Sidharth"
print(Name[5]) #Here we are specifying the index location to print

```

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Ans:
```python:
string = "Big Data iNeuron"
print(string[9:])
```

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Ans:
```python:
string = "Big Data iNeuron"
print(string[:-8:-1])
```

Q30. Reverse the string given in the above question.
Ans:
```python:
string = "Big Data iNeuron"
print(string[::-1])
```

Q31. How can you delete entire string at once?
Ans:
We can delete the entire using the keyword del.
```python:
string = "abc"
del string

```

Q32. What is escape sequence?

Ans: 
To insert characters that are illegal in a string, use an escape sequence.
An escape sequence is a backslash \ followed by the character you want to insert

Q33. How can you print the below string?
'iNeuron's Big Data Course'

Ans:

```python:
string = "\'iNeuron's Big Data Course\'"
print(string)
```

Q34. What is a list in Python?

Ans: 
Lists are used to store multiple items in a single variable.

Q35. How can you create a list in Python?

Ans:
```python:
list=["a","b","c"]
```

Q36. How can we access the elements in a list?

Ans:
```python:
list=["a","b","c"]
print(list[1])
```

Q37. Write a code to access the word "iNeuron" from the given list.
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]

Ans:
```python:
list = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(list[4][2])
```

Q38. Take a list as an input from the user and find the length of the list.

Ans:
```python:
x = list(input("Enter values: ").split())
print("Length of list: ",len(x))
```

Q39. Add the word "Big" in the 3rd index of the given list.
lst = ["Welcome", "to", "Data", "course"]

Ans:
```python:
list = ["Welcome", "to", "Data", "course"]
list.insert(3, "Big")
print(list)
```

Q40. What is a tuple? How is it different from list?

Ans:
The primary difference between tuples and lists is that tuples are immutable as opposed to lists which are mutable. 
Therefore, it is possible to change a list but not a tuple.

Q41. How can you create a tuple in Python?

Ans:

```python:
tuple=("1","2","3")
```

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Ans:
No since the tuple is immutable we can't make any changes to the existing tuple.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Ans:
```python:
tuple1=("1","2","3")
tuple2=("4","5","6")
tuple3=tuple1+tuple2
```

Q44. Take a tuple as an input and print the count of elements in it.

Ans:
```python:
x = tuple(input("Enter values: ").split())
print("Length of tuple: ",len(x))
```

Q45. What are sets in Python?

Ans:
A Set is an unordered collection data type that is iterable, mutable and has no duplicate elements. 

Q46. How can you create a set?
Ans:
```python:
var = {"A", "B", "C"}
```

Q47. Create a set and add "iNeuron" in your set.

Ans:
```python:
var = {"A", "B", "C"}
var.add("iNeuron")
```

Q48. Try to add multiple values using add() function.

Ans:
It throws an error as we can only add a single element

Q49. How is update() different from add()?

Ans:
Update can add multiple elemnts to the set.

Q50. What is clear() in sets?

Ans:
It will clear all the elements in the set.

Q51. What is frozen set?

Ans:
Python frozenset() Method creates an immutable Set object from an iterable. It is a built-in Python function.
As it is a set object therefore we cannot have duplicate values in the frozenset.

Q52. How is frozen set different from set?

Ans: 
It is immutable while normal set are not.


Q53. What is union() in sets? Explain via code.

Ans:
```python:
A = {0, 2, 4, 6, 8};
B = {1, 2, 3, 4, 5};
print("Union :", A | B)    #prints all the elements from both the sets
```

Q54. What is intersection() in sets? Explain via code.

Ans:
```python:
A = {0, 2, 4, 6, 8};
B = {1, 2, 3, 4, 5};
print("Intersection :", A & B)   #prints the elements available in both the sets
```

Q55. What is dictionary in Python?

Ans:
Dictionaries are used to store data values in key:value pairs.
A dictionary is a collection which is ordered*, changeable and do not allow duplicates.

Q56. How is dictionary different from all other data structures.

Ans:

It is differnt as other data structures conatins only value but dictionary calso contains the key for the value.

Q57. How can we delare a dictionary in Python?

Ans:
```python:
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
print(thisdict)
```

Q58. What will the output of the following?

var = {}
print(type(var))

Ans:
<class 'dict'>


Q59. How can we add an element in a dictionary?

Ans:
The update() method will update the dictionary with the items from a given argument. If the item does not exist, the item will be added.
```
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
thisdict.update({"color": "red"})
```

Q60. Create a dictionary and access all the values in that dictionary.

Ans:

```
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}
x = thisdict["model"]
```

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Ans:
```pyhton:
people = {1: {'name': 'John', 'age': '27', 'sex': 'Male'},
          2: {'name': 'Marie', 'age': '22', 'sex': 'Female'}}

print(people[1]['name'])
print(people[1]['age'])
print(people[1]['sex'])
```

Q62. What is the use of get() function?

Ans:
The get() method returns the value of the item with the specified key.

Q63. What is the use of items() function?

Ans:
Returns a list containing a tuple for each key value pair

Q64. What is the use of pop() function?

Ans:
Removes the element with the specified key

Q65. What is the use of popitems() function?

Ans:
Removes the last inserted key-value pair

Q66. What is the use of keys() function?

Ans:
Returns a list containing the dictionary's keys

Q67. What is the use of values() function?

Ans:
Returns a list of all the values in the dictionary

Q68. What are loops in Python?

Ans:
Looping means repeating something over and over until a particular condition is satisfied

Q69. How many type of loop are there in Python?

Ans:
There are two types of loops in Python, for and while.

Q70. What is the difference between for and while loops?

Ans:
A for loop in Python is used to iterate over a sequence while a The while loop is used to execute a set of statements as long as a condition is true.

Q71. What is the use of continue statement?

Ans:
Continue statement is used to skip to the next iteration in the loop.

Q72. What is the use of break statement?

Ans:
Break statement is used to break out of the loop. 

Q73. What is the use of pass statement?

Ans:
The pass statement is used as a placeholder for future code.

Q74. What is the use of range() function?

Ans:
The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

Q75. How can you loop over a dictionary?
Ans:
```
for x in thisdict:
  print(thisdict[x])
```

Coding problems
Q76. Write a Python program to find the factorial of a given number.
Ans:
```python:
x=int(input("Enter the number"))
res=1
for i in range(x,0,-1):
    res=res*i

print("Factorial is:", res)
```

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
```python:
p=int(input("Enter the Principal "))
r=int(input("Enter the Rate of Interest "))
t=int(input("Enter the Time(in Years) "))

print("Simple Interest is",(p*r*t)/100)
```


Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

```python:

p=int(input("Enter the Principal "))
r=int(input("Enter the Rate of Interest "))
t=int(input("Enter the Time(in Years) "))

print("Compound Interest is",p*((1+(r/100))**t ))


```

Q79. Write a Python program to check if a number is prime or not.
Ans:
```python:
x=int(input("Enter the number "))
res=1
flag=False
for i in range(2,x):
    if(x%i==0):
        flag=True
        break

if flag==True:
    print("The number is non prime number")
else:
    print("the number is a prime number")
```


Q80. Write a Python program to check Armstrong Number.
Ans:

```python:
num = int(input("Enter a number: "))
sum = 0
temp = num
while temp > 0:
   digit = temp % 10
   print(digit)
   sum += digit ** 3
   temp //= 10

if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
```

Q81. Write a Python program to find the n-th Fibonacci Number.
Ans:

```python:
x=int(input("Enter the number "))
res=[0,1]

for i in range(x-2):
   res.append(int(res[-1])+int(res[-2]))
   

print("The n'th Fibonacii number is",res[-1])

```

Q82. Write a Python program to interchange the first and last element in a list.
Ans:

```python:
list=[1,2,3,4]
temp=list[0]
list[0]=list[-1]
list[-1]=temp
print(list)
```

Q83. Write a Python program to swap two elements in a list.
Ans:
```python:
list=[1,2,3,4]
temp=list[0]
list[0]=list[-1]
list[-1]=temp
print(list)
```

Q84. Write a Python program to find N largest element from a list.
Ans:
```python:
l=[1,2,3,4]
l.sort(reverse=True)
n=input()
print(l[:n])
```

Q85. Write a Python program to find cumulative sum of a list.
Ans:
```python:
import functools

lis = [1, 3, 5, 6, 2]
 
print("The sum of the list elements is : ", end="")
print(functools.reduce(lambda a, b: a+b, lis))
 


```

Q86. Write a Python program to check if a string is palindrome or not.
Ans:
```python:
string="aabaa"
if string==string[::-1]:
    print("Palindrome")
else:
    print("Not a paindrome")

```

Q87. Write a Python program to remove i'th element from a string.
Ans:
```python:
string="abcdefgh"
i=int(input("Enter the i'th element"))
string1=string[:i-1]
string2=string[i:]
string=string1+string2
print(string)
```

Q88. Write a Python program to check if a substring is present in a given string.
Ans:
```python:
string = "abcdefghi"
 
if "abc" in string:
    print("Yes! it is present in the string")
else:
    print("No! it is not present")


```

Q89. Write a Python program to find words which are greater than given length k.
Ans:
```python:
string="a bcd efg dbfkjdbjf"
k=4
for i in string.split():
    if len(i)>=k:
        print(i)
    else:
        continue

```

Q90. Write a Python program to extract unquire dictionary values.
Ans:
```python:
test_list = [{'gfg': 1, 'is': 2}, {'best': 1, 'for': 3}, {'CS': 2}]
 
print("The original list : " + str(test_list))
res = list(set(val for dic in test_list for val in dic.values()))
print("The unique values in list are : " + str(res))
```

Q91. Write a Python program to merge two dictionary.
Ans:
```python:
dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}
dict2.update(dict1)
```

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Ans:
```python:
tups = [("akash", 10), ("gaurav", 12), ("anand", 14), 
    ("suraj", 20), ("akhil", 25), ("ashish", 30)]
dictionary = dict(tup)
print(disctionary)

```
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Ans:
```python:
list1 = [9, 5, 6]
res = [(val, pow(val, 3)) for val in list1]

```
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Ans:
```python:

a=(7,2) 
b=(7,8)
res =  [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res +  [(a, b) for a in test_tuple2 for b in test_tuple1]

```

Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Ans:
```python:
def Sort_Tuple(tup):
    tup.sort(key = lambda x: x[1])
    return tup
 
 tup =  [('for', 24), ('Geeks', 8), ('Geeks', 30)]
 
 print(Sort_Tuple(tup))

```
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Ans:

```python:

rows = 5
for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print("*", end=' ')
    print('')
```
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Ans:
```python:

rows = int(input("Enter the number of rows:"))  
k = 2 * rows - 2 
for i in range(0, rows):  
    for j in range(0, k):  
        print(end=" ")  
    k = k - 2     
    for j in range(0, i + 1):  
        print("* ", end="") 
    print("")  
    
```
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 

Ans:
```python:
n = int(input("Enter the number of rows: "))  
m = (2 * n) - 2  
for i in range(0, n):  
    for j in range(0, m):  
        print(end=" ")  
    m = m - 1  # decrementing m after each loop  
    for j in range(0, i + 1):  
        # printing full Triangle pyramid using stars  
        print("* ", end=' ')  
    print(" ")  


```
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5

Ans:
```python:

rows = int(input("Enter the number of rows: "))  
  
# This will print the rows  
for i in range(1, rows+1):  
    # This will print number of column  
    for j in range(1, i + 1):  
        print(j, end=' ')  
    print("")  


```
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 

Ans:
```python:

for i in range (65,70):
    # inner loop
    for j in range(65,i+1):
        print(chr(i),end="")
    print()

```


