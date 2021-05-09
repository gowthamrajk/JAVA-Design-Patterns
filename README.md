# JAVA DESIGN PATTERNS

This module consists of the Detailed definitions about the JAVA Design Patterns and their practical implementation through Codes.

some of the Design Patterns available in JAVA are:

- Singleton Design Pattern
- Factory Design Pattern
- Builder Design Pattern
- Prototype Design Pattern
- Proxy Design Pattern
- Facade Design Pattern
- Composite Design Pattern
- Decorator Design Pattern
- Flyweight Design Pattern
- Adapter Design Pattern
- Bridge Design Pattern
- Observer Design Pattern 

# Singleton Design Pattern

- Singleton pattern is one of the simplest design patterns in Java. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.
- This pattern involves a single class which is responsible to create an object while making sure that only single object gets created. This class provides a way to access its only object which can be accessed directly without need to instantiate the object of the class.

![image](https://user-images.githubusercontent.com/43011442/117574182-83d43580-b0f9-11eb-8cc9-c799a659f0e8.png)

# Factory Design Pattern

- Factory pattern is one of the most used design patterns in Java. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.
- In Factory pattern, we create object without exposing the creation logic to the client and refer to newly created object using a common interface.

![image](https://user-images.githubusercontent.com/43011442/117574213-abc39900-b0f9-11eb-9cc3-f601b8c2c223.png)

# Builder Design Pattern

- Builder pattern builds a complex object using simple objects and using a step by step approach. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.
- A Builder class builds the final object step by step. This builder is independent of other objects.

![image](https://user-images.githubusercontent.com/43011442/117574235-c990fe00-b0f9-11eb-8b8d-5c20c5388047.png)

# Prototype Design Pattern

- Prototype pattern refers to creating duplicate object while keeping performance in mind. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.
- This pattern involves implementing a prototype interface which tells to create a clone of the current object. This pattern is used when creation of object directly is costly. For example, an object is to be created after a costly database operation. We can cache the object, returns its clone on next request and update the database as and when needed thus reducing database calls.

![image](https://user-images.githubusercontent.com/43011442/117574418-9b5fee00-b0fa-11eb-9143-880e563fc020.png)

# Proxy Design Pattern

- In proxy pattern, a class represents functionality of another class. This type of design pattern comes under structural pattern.
- In proxy pattern, we create object having original object to interface its functionality to outer world.

![image](https://user-images.githubusercontent.com/43011442/117574433-ae72be00-b0fa-11eb-8d4a-5bbea4c4a744.png)

# Facade Design Pattern

- Facade pattern hides the complexities of the system and provides an interface to the client using which the client can access the system. This type of design pattern comes under structural pattern as this pattern adds an interface to existing system to hide its complexities.
- This pattern involves a single class which provides simplified methods required by client and delegates calls to methods of existing system classes.

![image](https://user-images.githubusercontent.com/43011442/117574467-d4985e00-b0fa-11eb-96fe-69a3218f9952.png)

# Composite Design Pattern

- Composite pattern is used where we need to treat a group of objects in similar way as a single object. Composite pattern composes objects in term of a tree structure to represent part as well as whole hierarchy. This type of design pattern comes under structural pattern as this pattern creates a tree structure of group of objects.
- This pattern creates a class that contains group of its own objects. This class provides ways to modify its group of same objects.

![image](https://user-images.githubusercontent.com/43011442/117574495-ef6ad280-b0fa-11eb-9ce1-8153da0059c6.png)

# Decorator Design Pattern

- Decorator pattern allows a user to add new functionality to an existing object without altering its structure. This type of design pattern comes under structural pattern as this pattern acts as a wrapper to existing class.
- This pattern creates a decorator class which wraps the original class and provides additional functionality keeping class methods signature intact.

![image](https://user-images.githubusercontent.com/43011442/117574697-ef1f0700-b0fb-11eb-9d88-794867df11a3.png)

# Flyweight Design Pattern

- Flyweight pattern is primarily used to reduce the number of objects created and to decrease memory footprint and increase performance. This type of design pattern comes under structural pattern as this pattern provides ways to decrease object count thus improving the object structure of application.
- Flyweight pattern tries to reuse already existing similar kind objects by storing them and creates new object when no matching object is found.

![image](https://user-images.githubusercontent.com/43011442/117574668-dadb0a00-b0fb-11eb-957b-b51b1dc3450d.png)

# Adapter Design Pattern
