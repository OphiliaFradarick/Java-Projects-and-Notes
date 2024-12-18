#Override and Overloading 
![image](https://github.com/user-attachments/assets/fd2f756c-2f56-48ab-87a7-a4a2606a16db)
When you override a parent class method in a child class, you can insert an override annotation just prior to the method. 
The @Override annotation lets the compiler know that your intention is to override a method in the parent class rather than create a method with a new signature.
![image](https://github.com/user-attachments/assets/6f0e114f-122b-4124-9170-79cb19b36bf5)

Inheritance
![image](https://github.com/user-attachments/assets/0c436f8e-1d73-449c-83e2-4b4ed32ffcc0)

Polymorphism
![image](https://github.com/user-attachments/assets/2af3ae15-6faf-46a2-870c-d2dea31c7be3)
Using the same method name to indicate different implemenatation is called polymorphism - A term meaning many forms
many different forms of action take place, eventhiugh you see the same word to describe the action.
If a programming language does not support polymorphism, the language is not considered as object oriented. 
It is important to note that each subclass method overrides any method in the parent class that has both the same name and parameter list.
If the parent class method has the same name but different parameter list, the subclass method does not iverride the parent class. Instead the suclass method overloads the parent class method and any subclass object has access too both versions.


# Abstract classes
A concrete class is one from which you can instantiate objects. Sometimes, a class is so general that you never intend to create any specific instances of the class.

In Java, an abstract class is a class that cannot be instantiated on its own. Instead, it serves as a blueprint for other classes. It can contain both abstract methods (methods without a body) and concrete methods (methods with a body). Abstract classes are used when you want to define a base class that provides common functionality but also allows subclasses to implement or override specific behaviors.

When making abstarct declarations:
1) If you declare a class to be abstract, each of it's methods can be abstract or not. A abstract class cannot create objects.
2)
