## IOS Design Patterns ##

The SOLID principles are the foundation for the implementing/creating effective, maintainable, scalable and loosely coupled system.

## SOLID stands for what? ##


S for Single Responsibility Principle

O for Open Closed Principle

L for Liskov substituation principle

I for Interface segeragation principle

D for Dependecy inversion principle



## Single Responsibility Principle ##

Class should have only one reason to change. It can be changed multiple time over the period of time but within the context of that class. In simple word, it should have the contextual reason to change in the class.

E.g, if you are fetching a location of a user, it shoudl only fetch a location of user. if its model class - it should represent only one entity


## Open Closed Principle (OCP)  ##

"Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification." -The Open-Closed Principle

If you want to create a class that is easy to maintain, it must have two important characteristics:

Open for extension:  You should be able to extend or change the behaviors of a class without efforts.

Closed for modification: You must extend a class without changing the implementation. You can achieve these characteristics thanks to the abstraction.

E.g. – Have a look at the Spring framework in java. You cannot modify its logic but you can create application flow by extending its classes.


## The Liskov Substitution Principle (LSP) ##

"Functions that use pointers of references to base classes must be able to use objects of derived classes without knowing it." -The Liskov Substitution Principle


Inheritance may be dangerous and you should use composition over inheritance to avoid a messy codebase, even more so if you use inheritance in an improper way


