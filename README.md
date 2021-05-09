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

