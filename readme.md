# ReadMe
## Refer below Cmds for Output:

![outputpictureofFactorMethodPattern ](https://user-images.githubusercontent.com/40432616/180643463-b101bdb9-4541-4387-8603-36dd40b5d03d.jpg)


## below, link are 
for the refs:
### https://www.javatpoint.com/singleton-design-pattern-in-java


# Singleton design pattern in Java

## Advantage of Singleton design pattern
### Saves memory because object is not created at each request. Only single instance is reused again and again.
## Usage of Singleton design pattern
### Singleton pattern is mostly used in multi-threaded and database applications. It is used in logging, caching, thread pools, configuration settings etc.


# Prototype Design Pattern
## Prototype Pattern says that cloning of an existing object instead of creating new one and can also be customized as per the requirement.
## This pattern should be followed, if the cost of creating a new object is expensive and resource intensive.


# Advantage of Prototype Pattern
## The main advantages of prototype pattern are as follows:

It reduces the need of sub-classing.
It hides complexities of creating objects.
The clients can get new objects without knowing which type of object it will be.
It lets you add or remove objects at runtime.
## Usage of Prototype Pattern
When the classes are instantiated at runtime.
When the cost of creating an object is expensive or complicated.
When you want to keep the number of classes in an application minimum.
When the client application needs to be unaware of object creation and representation.



# Builder Design Pattern

### Builder Pattern says that "construct a complex object from simple objects using step-by-step approach"
### It is mostly used when object can't be created in single step like in the de-serialization of a complex object.


# Object Pool Pattern


### Mostly, performance is the key issue during the software development and the object creation, which may be a costly step.
### Object Pool Pattern says that " to reuse the object that are expensive to create".
### Basically, an Object pool is a container which contains a specified amount of objects. When an object is taken from the pool, it is not available in the pool until ### it is put back. Objects in the pool have a lifecycle: creation, validation and destroy.
### A pool helps to manage available resources in a better way. There are many using examples: especially in application servers there are data source pools, thread ### pools etc.



