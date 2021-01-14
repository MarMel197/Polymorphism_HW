# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

A - Polymorphism is the defination of when something can take "Many forms".

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example. 

A -  Polymorphism is when we have several classes that inherit a common behaviour through methods from another class thet aren't necessarily dirctly related to.

3. What can we use to implement polymorphism in Java?

A - Method overloading allow us to implement polymorphism in Java ie - when you have two methods with the same name and Java will know which one to use based on the parameters being passed in.

4. How many 'forms' can an object take when using polymorphism?

A - I think it's unlimited but convention is 3 or 4 at the most to avoind complexity

5. Give an example of when you could use polymorphism.

A -  So for example we may have a male & female class that extends a human super class. From this we can create people that for example share the ability to talk which was inherrited from the human class.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

A - Composition in OOP is when one object "HAS" a relationship with another object. For Example a car may have an engine.

7. When would you use composition? Provide a simple example in Java.

A - You might use a method from an engine class to bring that functionality to your car object using composition.

8. What is/are the advantage(s) of using composition?

A - Not having to re-write functionality to carry out the same tasks keeping your code "Dry".

9. When an object is destroyed, what happens to all the objects it is composed of?

A - I'm presuming all the objects remain intact ie. If you made a Ford object by inheriting from a Car class and it gets an engine functionality from an engine class these would remain isolated and protected if the Ford object was deleted.