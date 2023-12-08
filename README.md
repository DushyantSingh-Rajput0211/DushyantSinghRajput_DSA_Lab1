# DushyantSinghRajput_DSA_Lab1
## DSA_Lab1_EmailApplication

GitHub [link](https://github.com/DushyantSingh-Rajput0211/DushyantSinghRajput_DSA_Lab1/tree/main/Email-Application) for the project.


### Problem Statement:
```
You are an IT Support Administrator and are charged with the task of creating credentials for
new hires
Your application should do the following:
a) Generate an email with the following syntax
firstNamelastName@department.company.com
b) Determine the department (Technical, Admin, Human Resource, Legal)
c) Generate a random password which will contain (number, capital letter, small letter &
special character)
d) Display the generated credentials
e) Use parameterized constructor of class Employee, to pass firstName, lastName.
f) Create a separate CredentialService which will have generatePassword,
generateEmailAddress, & showCredentials method.
```

```What is OOPs?```

```
OOPs stands for Object-Oriented Programming. It is a programming paradigm that is centered around the concept of "objects,"
which can contain data in the form of fields (often known as attributes or properties) and code, in the form of procedures
(often known as methods).
```
The ```main principles``` of Object-Oriented Programming include:

### 1. Encapsulation:

Encapsulation refers to the bundling of data and the methods that operate on that data into a single unit, known as a class. It helps hide an object's internal details and expose only what is necessary.

### 2. Inheritance:

Inheritance is a mechanism that allows a class (subclass or derived class) to inherit the properties and behaviors of another class (superclass or base class). It promotes code reuse and establishes a relationship between classes.

### 3. Polymorphism:

Polymorphism allows objects of different types to be treated as objects of a common type. It enables a single interface to represent different types and allows methods to be consistently applied to objects of various classes.

### 4. Abstraction:

Abstraction involves simplifying complex systems by modeling classes based on the essential properties and behaviors they share. It provides a way to create abstract classes and interfaces, allowing programmers to focus on the essential features of an object.
These principles help organize code in a modular and reusable way, making it easier to manage, scale, and maintain. Object-oriented programming is widely used in software development and has become a fundamental concept in many programming languages, including Java, C++, Python, and others.

```Use of New Classes```
#### 1. StringBuilder
StringBuilder in Java is a mutable class for efficiently manipulating sequences of characters. It provides methods for tasks like concatenation, insertion, deletion, and replacement of strings. Unlike the immutable String class, StringBuilder allows modifications without creating new objects, making it efficient for string manipulations. It's not thread-safe but offers better performance in a single-threaded context compared to StringBuffer.

#### 2. Random
The Random class in Java, part of java.util, is used to generate pseudorandom numbers. It produces deterministic yet seemingly random sequences, making it suitable for various applications. Instances can be initialized with a seed for reproducibility. Common methods include nextInt(), nextDouble(), and nextBoolean(). While not inherently thread-safe, it is advised to use separate instances for concurrent threads. It provides a simple and versatile way to introduce randomness in Java programs for tasks such as simulations, games, or any scenario requiring unpredictable values.

```How to run the project:```
```
1. Copy the GitHub link.
2. Open the folder where you want to clone the project
3. Open Terminal
4. Write the following command: git clone <Project_Link>
5. Open this project in your IDE (IntelliJ, Eclipse)
6. Right-click -> Run As -> Java Application.
7. Enter your FirstName, LastName and select the department in the Console.
```
