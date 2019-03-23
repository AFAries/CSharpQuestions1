#### CSharpQuestions1

I included all the links which I used references/sources but the definitions/answers I tried to explain in a simpler fashion.

1.	Q: What is a namespace?

A namespace is one way to help organize your programming project. A namespace is a method for organizing your code adding clarity and keeping object names from interfering with each other.
https://www.tutorialspoint.com/csharp/csharp_namespaces.htm

2.	Q: What are value types?

Value Types are variables that can be assigned a value directly, so they are basically part of your bread and butter for programing. Integers and floats are variables under this category.
https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/types

3.	Q: What are reference types?

Reference types are your other bread and butter item for programming. They are variables, but unlike they value types, they contain references to data and don’t actually contain data itself.
https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/types

4.	Q: What is an automatic property and how is it useful?

Automatic properties are basically shortcuts for coding, simplifying code and saving on logical input.
https://stackoverflow.com/questions/6001917/what-are-automatic-properties-in-c-sharp-and-what-is-their-purpose

5.	Q: What is the purpose of using statement?

“The reason for the using statement is to ensure that the object is disposed as soon as it goes out of scope, and it doesn’t require explicit code to ensure this happens.”
Therefore a using statement can act sort of as a shortcut for coding, saving one from additional typing. Basically logic saving.

https://stackoverflow.com/questions/75401/what-are-the-uses-of-using-in-c-sharp

6.	Q: What are dynamic type variables?

Dynamic type variables are variables where type checking occurs at run time instead of compile time. Sort of like checking things at the gate of a race instead of during it.

https://stackoverflow.com/questions/2690623/what-is-the-dynamic-type-in-c-sharp-4-0-used-for
https://www.tutorialsteacher.com/csharp/csharp-dynamic-type

7.	Q: What is the purpose of the is operator?

The is operator checks if an object is compatible with a given type. Basically, it’s like checking if “A” = “B”.

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/is

8.	Q: What are generics and how is using them useful?

“Generics allow you to define the specification of the data type of programming elements in a class or a method, until it is actually used in the program.”
Generics are basically flexible data types you can use in your code to make it easier.

https://www.tutorialspoint.com/csharp/csharp_generics.htm

9.	Q: What is the scope of a public member of a class?

The scope of a public member class is that it can be accessed by any other code/assembly that references it. Meaning its sort of available to anything.

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers

10.	Q: Can you create a function that can accept a varying number of arguments?

You can create a function that can accept a varying number of arguments using the “params” keyword.

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/params

11.	Q: How do you sort an array?

You can use an Array.Sort method for your array/code.

https://docs.microsoft.com/en-us/dotnet/api/system.array.sort?view=netframework-4.7.2

12.	Q: What is a nullable type and what purpose does it serve?

A nullable type is a variable with a blank value/null. For example, you can sort of use it like a global variable when you want to get values from a user.

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/nullable-types/

13.	Q: What is an enumeration?

Enumeration is a set of named integer constants and contain their own values. Enums are baselines of code.

https://www.tutorialspoint.com/csharp/csharp_enums.htm

14.	Q: What is inheritance?

Inheritance is the idea of passing methods/properties between a main class to its subclass. Sort of like a parent to a child where the kid will inherit its parents traits.

https://www.guru99.com/c-sharp-inheritance-polymorphism.html

15.	Q: Is multiple inheritance supported?
C# doesn’t allow multiple inheritances, the closest thing you can get to that would be using an Interface. For example, you can't use multiple abstract classes.

https://stackoverflow.com/questions/2456154/does-c-sharp-support-multiple-inheritance

16.	Q: What is the purpose of as operator

The as operator is used perform an operation without raising an exception. In a way, it is sort of like error/fact checking code.

https://stackoverflow.com/questions/3160127/whats-the-point-of-as-keyword-in-c-sharp

17.	Q: What is an object?

An object is an instance of a class and it contains both values and properties. Sort of like a car with its components.

https://www.guru99.com/c-sharp-class-object.html#1

18.	Q: What is the difference between a struct and a class?

The difference between a structure and a class is a structure is structures are value types and classes are reference types.

https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/choosing-between-class-and-struct

19.	Q: What is the difference between continue and break statements?

A break statement exits the loop while a continue skips the current loop iteration. Simply put, you break, you leave, you continue, you skip ahead.

https://stackoverflow.com/questions/6414/c-sharp-loop-break-vs-continue

20.	Q: What is this and how is it used?

“This” is used to refer to the current instance of the class. It can be used to qualify members of a class.

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/this

21.	Q: What is try and catch and when are they used?

Try and catch are both part of exception handling. Try is an attempt at running a block of code, where a catch is trying to “find” and “catch” an error if one appears. You want to use them any time you think you’ll encounter an exception and/or potentially crash your program.

https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm

22.	Q: How is exception handling done?

An exception occurs when an error arises when the program is run. There are four things primarily related with exception handling, they are: try, catch, finally, and throw. A try is attempting a list/block of code, and a catch is what you will use if you encounter a problem/exception. A finally runs regardless of an exception and a throw does as it name implies, throws the exception.

https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm

23.	Q: What is finally and what is its purpose?

Answered before on the previous question, but a finally statement runs a block of code regardless if an exception occurred.

https://www.tutorialspoint.com/csharp/csharp_exception_handling.htm

24.	Q: List the differences between Array and ArrayList.

An Array is a variable that can hold elements of the same type and is declared with a specific length upon its creation. An Array List is similar to an Array; however, it doesn’t have to have its length declared beforehand. Also, a major difference is the flexibility between the two. An ArrayList can store any type of element and this makes it more flexible besides the fact it doesn’t have to have a predetermined length on its creation. Also/therefore an ArrayList is not strongly typed.

https://www.tutorialsteacher.com/articles/difference-between-array-and-arraylist-in-csharp

25.	Q: What is an object?

This was asked before on Question 17, but an object is an instance of a class and it contains both values and properties.

https://www.guru99.com/c-sharp-class-object.html#1

26.	Q: Define constructor.

A constructor is an instance of a class. An instance itself is like the house that came from your blueprints.

https://stackoverflow.com/questions/1130199/methods-and-constructors

27.	Q: When can var be used to declare a variable and how is the type for the variable determined?

Var can be used to declare a variable without using an initializer. It’s determined by the compiler. So it can save some typing.

https://stackoverflow.com/questions/4307467/what-does-var-mean-in-c

28.	Q: What is an abstract class?

An abstract class is a class that can’t be instantiated, meaning it can’t create a new instance of a class. You use it sort of as the building block for other classes, sort of like blueprints.

https://www.guru99.com/c-sharp-abstract-class.html

29.	Q: What is an interface?

An interface contains only the declaration of what a class will provide to a program (methods). So, it’s basically what the program can/can’t do.

https://www.guru99.com/c-sharp-interface.html

30.	Q: What is a method?

A method is code used to tell the program what computations/operations (Do's/Don'ts) can be performed on the data.

https://www.guru99.com/c-sharp-class-object.html

31.	Q: What is a property?

“A property is a member that provides a flexible mechanism to read, write, or compute the value of a private field.”
To put it in another way, it allows a level of abstraction with your code.

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/properties

32.	Q: What is an access specifier?

An access specifier is used for types and members to specify how accessible they are in your code. "Public" and "private" are two primary examples of this.

https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers

33.	Q: What access specifiers are supported and what do they mean?

C# access specifiers that are supported are: public, protected, internal, protected internal, private, and private protected.

Public is not protected/restricted.

Protected is “limited to the containing class or types derived from the containing class.”

Internal is “limited to the current assembly.”

Protected internal is limited to the current assembly or types derived from the containing class.”

Private is “limited to the containing type.”

Private Protected is “limited to the containing class or types derived from the containing class within the current assembly.”

Basically as said on the previous question, they are used to tell how available your code is.

https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/accessibility-levels

34.	Q: What is a collection?

A collection is a flexible class to group objects. Flexible meaning it isn't bound by length nor element type.

https://www.guru99.com/c-sharp-collections.html

35.	Q: What is a Hash Table?

A hash table is a “collection used to store key-value items.” It’s sort of like a dictionary but is not generically typed.

https://stackoverflow.com/questions/876656/difference-between-dictionary-and-hashtable

https://www.guru99.com/c-sharp-hashtable.html
