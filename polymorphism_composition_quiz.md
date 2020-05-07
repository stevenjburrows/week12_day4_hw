# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

It is where an object can take on different forms 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

This is where a Java object can pass more than one __IS-A__ test

public class TRex extends Dinosaur implements Carnivor, Teeth

3. What can we use to implement polymorphism in Java?

We can use interfaces to implement polymorphism


4. How many 'forms' can an object take when using polymorphism?

The is no limit but it should be restricted to as many as needed.

5. Give an example of when you could use polymorphism.

When you want to force an object to use caertain variables or allow it to be as a differenct type. Like in the example above you could force tex to have a int NoOfTeeth or cast the tTRex as type Carnivor 



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

this is where an class __HAS-A__ relationship with another class

7. When would you use composition? Provide a simple example in Java.

When you need somehting form another class but not forced

public class Dog {

	private Trick trick1;


8. What is/are the advantage(s) of using composition?

reuse of code and able to add more than one in a class

9. When an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed.

