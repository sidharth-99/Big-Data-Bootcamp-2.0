
Q1. What is the purpose of Python's OOP?

Ans:
Object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming.

Q2. Where does an inheritance search look for an attribute?

Ans:
An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right (by default). The search stops at the first place the attribute is found.


Q3. How do you distinguish between a class object and an instance object?

Ans: If the variable is defined in the class then it is a class variable. If the object is defined in the Constructor ten it is an instance variable.


Q4. What makes the first argument in a class’s method function special?

Ans: Python does not use special syntax to refer to instance attributes. The first parameter of methods is the instance the method is called on. We generally give it's name as 'self' and it is just to specify the object.

Q5. What is the purpose of the init method?

Ans: The init method allows you to accept arguments to your class. More importantly, the __init__ method allows you to assign initial values to various attributes on your class instances.

Q6. What is the process for creating a class instance?

Ans: To create instances of a class, you call the class using class name and pass in whatever arguments its init method accepts.

Q7. What is the process for creating a class?

Ans: We can create a class with the keyword class.

Q8. How would you define the superclasses of a class?

Ans: The class from which a class inherits is called the parent or superclass.


Q9. What is the relationship between classes and modules?

Ans: Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables).


Q10. How do you make instances and classes?

Ans: To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts. To make a class you need to define it with the keyword class.


Q11. Where and how should be class attributes created?

Ans: Class Attributes should be created in the class itself.

```
class car:
  wheels=4
  
```
Here wheels is a class attribute

Q12. Where and how are instance attributes created?

Ans:

```
class Employee:

    # Class attribute
    # Constructor of class
    # it is mainly used for assignment of instance variables
    def __init__(self, name, salary ):
        # instance variable or instance attributes
        self.emp_name = name
        
```
Here name and salary deifned in the Constructor are the instance attributes.


Q13. What does the term "self" in a Python class mean?

Ans: Python does not use special syntax to refer to instance attributes. The first parameter of methods is the instance the method is called on. We generally give it's name as 'self' and it is just to specify the object.

Q14. How does a Python class handle operator overloading?

Ans: 

```
class A:
    def __init__(self, a):
        self.a = a
 
    # adding two objects
    def __add__(self, o):
        return self.a + o.a
ob1 = A(1)
ob2 = A(2)
ob3 = A("Geeks")
ob4 = A("For")
 
print(ob1 + ob2)
print(ob3 + ob4)
# Actual working when Binary Operator is used.
print(A.__add__(ob1 , ob2))
print(A.__add__(ob3,ob4))
#And can also be Understand as :
print(ob1.__add__(ob2))
print(ob3.__add__(ob4))
```

Q15. When do you consider allowing operator overloading of your classes?

Ans: When you need to use specific operators for different data types.

Q16. What is the most popular form of operator overloading?

Ans: Addition of two dat types is a popular form of operator overloading.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

Ans: Inheritance and Polymorphism.


Q18. Describe three applications for exception processing.

Ans: There are mainly three kinds of distinguishable errors in Python: syntax errors, exceptions and logical errors. For this e need to process the exceptions.


Q19. What happens if you don't do something extra to treat an exception?

Ans: The program terminates abruptly and the code past the line that caused the exception will not get executed.


Q20. What are your options for recovering from an exception in your script?

Ans: We can handle the exception with inbuilt python commands. We generally do this by catching the exception using try except block.

Q21. Describe two methods for triggering exceptions in your script.

Ans: 2 methods include
     1) try
     2) Except

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.

Ans: we can use finally method for the same feature to be implemented.

Q23. What is the purpose of the try statement?

Ans: The try block lets you test a block of code for errors

Q24. What are the two most popular try statement variations?

Ans: Most popular variations include
     1) Basic try except
     2) Try excpet with if else
     3) Catching specific exceptions
     4) try with finally statement

Q25. What is the purpose of the raise statement?

Ans: This keyword can be used to manually raise an exception.

Q26. What does the assert statement do, and what other statement is it like?

Ans: The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError.

Q27. What is the purpose of the with/as argument, and what other statement is it like?

Ans: The with statement is a replacement for commonly used try/finally error-handling statements

Q28. What are *args, **kwargs?

Ans: Python has *args which allow us to pass the variable number of non keyword arguments to function.

Q29. How can I pass optional or keyword parameters from one function to another?

Ans: Python passes variable length non keyword argument to function using *args but we cannot use this to pass keyword argument. For this problem Python has got a solution called **kwargs, it allows us to pass the variable length of keyword arguments to the function.

Q30. What are Lambda Functions?

Ans: A lambda function is a small anonymous function. A lambda function can take any number of arguments, but can only have one expression.

Q31. Explain Inheritance in Python with an example?

Ans: Inheritance allows us to define a class that inherits all the methods and properties from another class.
Parent class is the class being inherited from, also called base class.
Child class is the class that inherits from another class, also called derived class.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

Ans: that depends on the data type passed as parameters in the function. With respect to that the function gets executed.

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Ans: Python has two built-in functions that work with inheritance:
      Use isinstance() to check an instance's type: isinstance(obj, int) will be True only if obj.__class__ is int or some class derived from int .
      Use issubclass() to check class inheritance: issubclass(bool, int) is True since bool is a subclass of int .

Q34.Explain the use of the 'nonlocal' keyword in Python.

Ans: The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.

Q35. What is the global keyword?

Ans:  The global keyword allows us to modify the variable outside of the current scope. It is used to create a global variable and make changes to the variable in a local context.
