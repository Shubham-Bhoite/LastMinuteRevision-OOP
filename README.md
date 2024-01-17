# Object Oriented Programming Notes - Last Minute Revision ✅

##### Here we have last minute revision notes of object oriented programming language. These questions will familiarize you with the most important object-oriented programming concepts and help you ace your job interviews 🙌

--- 
### Most Asked OOPS Interview Questions ==>

## 1: What is OBJECT-ORIENTED PROGRAMMING?
- Object-oriented programming is a programming paradigm built on the concept of objects.
- In Other Words, it is an approach to problem-solving where all computations are carried out using objects.

## 2: Class and Object:
 Class: A class is the building block that leads to Object-Oriented programming. It is a user-defined datatype, which holds its own data members and member functions, which can be accessed and used by creating an instance of that class.

 Object: An Object is an instance of a Class. When a class is defined, no memory is allocated but when it is instantiated (i.e. an object is created) memory is allocated.

## 3: Constructor:
- Constructors are special class members which are called by the compiler every time an object of that class is instantiated.
- Constructors have the same name as the class looks like method and does not have return type.
- If we provide return type to constructor it becomes a method.
#### There are 3 types of constructors:
    1. Default constructors
    2. Parameterized constructors
    3. Copy constructors
- Default Constructor: Default constructor is the constructor which doesn’t take any argument. It has no parameters.
- Parameterized Constructor: A constructor is called Parameterized Constructor when it accepts a specific number of parameters.
- Copy Constructor: A copy constructor is a member function which initializes an object using another object of the same class.
### Characteristics of the constructor:
- Constructor has the same name as the class itself.
- Constructors don’t have a return type.
- A constructor is automatically called when an object is created.
- It must be placed in the public section of class.
- If we do not specify a constructor, C++ compiler generates a default constructor for object (expects no parameters and has an empty body).
- Constructors can be overloaded.
- Constructor cannot be declared virtual.

## 4: Destructor:
- A destructor is also a special member function as a constructor. Destructor destroys the class objects created by the constructor.
- Destructor has the same name as their class name preceded by a tiled (~) symbol.
### Characteristics of the constructor:
- Destructor is invoked automatically by the compiler when its corresponding constructor goes out of scope and releases the memory space that is no longer required by the program.
- Destructor neither requires any argument nor returns any value therefore it cannot be overloaded.
- Destructor cannot be declared as static and const.
- Destructor should be declared in the public section of the program.
       
## 5: The main features of OOPs?
- The main four pillar of oops are given below.
- ![image](https://github.com/Shubham-Bhoite/LastMinuteRevision-OOP/assets/117765637/d28b2139-be6b-485e-af8d-b58c22c61f9c)

## 6: Inheritance :
Inheritance is one of the most important features of Object-Oriented Programming. The capability of a class to derive properties and characteristics from another class is called Inheritance.
- Real Life Example
- ![image](https://github.com/Shubham-Bhoite/LastMinuteRevision-OOP/assets/117765637/b2f22891-5a09-45d6-9ef0-c729fe42cc94)

#### There are 5 types of Inheritance:
    1. Single Inheritance
    2. Multiple Inheritance
    3. Multilevel Inheritance
    4. Hierarchical Inheritance.
    5. Hybrid Inheritance.

1) Single Inheritance: When a subclass(child) is inherited from a base class is called single inheritance.
2) Multiple Inheritance: when one subclass is inherited from more than one base class is called multiple inheritance.
3) Multilevel Inheritance: In this type of inheritance, a derived class is created from another derived class.
4) Hierarchical Inheritance: In this type of inheritance, more than one subclass is inherited from a single base class.
5) Hybrid Inheritance: The inheritance in which the derivation of a class involves more than one form of any inheritance is called hybrid inheritance. Basically C++ hybrid inheritance is combination of two or more types of inheritance. It can also be called multi path inheritance.

## 7: Encapsulation :
- In normal term encapsulation is defined as wrapping up of data and information under a single unit.
- Encapsulation define as binding together the data and function that manipulates them.

### Advantages ==>
1) Increased security of data.
2) Encapsulation allows access to a level without revealing the complex details below that level.
3) It reduces human errors.
4) Makes the application easier to understand.

## 8: Abstraction :
- Data Abstraction is one of the most essential and important feature of Object Oriented Programming in c++.
- Abstraction means displays only the relevant attributes of objects and hides the unnecessary details like the background details and implementation.

### Advantages ==>
1) Helps user to avoid writing the low level code.
2) Avoids code duplication and increases reusability.
3) Helps to increase security of an application or program as only required details are provided to the user.

## 9: Polymorphism :
- The word polymorphism means having many forms. Polymorphism occurs when there is a hierarchical mode inheritance.
- C++ polymorphism means that a call to a member function will cause a different function to be executed depending on the type of object that invokes the function.
### There are 2 types of Polymorphism:
     1. Compile time Polymorphism
     2. Run time Polymorphism
### 1) Compile time Polymorphism: 
- Compile-time polymorphism is a polymorphism that is, the function call is resolved during the compilation process.
- We can achieve Compile-time polymorphism by two ways:
  1. Function overloading :
  - When there are multiple functions with the same name but take different parameters as an arguments then these function are said to be overloaded.
  - Functions can be overloaded by changing the number of arguments or and changing the type of arguments.
  2. Operator Overloading:
  - C++ also provides the option to overload operators So a single operator ‘+’, when placed between integer operands, adds them and when placed between string operands, concatenates them.
 
 ### 2) Runtime Polymorphism :
 - Runtime polymorphism is also known as dynamic polymorphism or late binding. In runtime polymorphism, the function call is resolved at run time.
 - This type of polymorphism is achieved by Function Overriding or Virtual function.

## 10: Abstract Class :
- Sometimes implementation of all function cannot be provided in a base class because we don’t know the implementation. Such a class is called abstract class. Example, let Shape be a base class. We cannot provide implementation of function draw() in Shape, but we know every derived class must have implementation of draw().
- Class is Abstract, if we have atleast one pure virtual function.

## 11:Interface :
- Interface looks like class
- It does not have constructor
- We can not create the object of the interface
- Use implement keyword to implements interface to class
- Use to achieve multiple inheritance

## 12: Pure Virtual Function :
- Also called Absract function.
- A pure virtual function in c++, is a virtual function for which we can have implementation, but we must override that function in the derived class, otherwise the derived class will also become abstract class.

## 13: Access Modifiers :
- Private – The access level of a private modifier is only within the class. It cannot be accessed from outside the class.
- Default – The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default.
- Protected – The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.
- Public – The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.
