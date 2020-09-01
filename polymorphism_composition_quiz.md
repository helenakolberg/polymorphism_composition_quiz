# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?  
**Answer:** Many forms  

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.  
**Answer:** We can treat a class as being of another type, e.g if a Car class implements the IDrive and IPark interfaces, we can also treat it as an IDrive/IPark type.  

3. What can we use to implement polymorphism in Java?  
**Answer:** Interfaces  

4. How many 'forms' can an object take when using polymorphism?  
**Answer:** Unlimited  

5. Give an example of when you could use polymorphism.  
**Answer:** If I need to manage multiple different classes with one particular method in common, these classes could implement a common interface and I could treat them as being of the interface type.  



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?  
**Answer:** When an object is made up of other objects.  

7. When would you use composition? Provide a simple example in Java.  
**Answer:** When an attribute of an object needs to have its own attributes, e.g a Cinema class has a Screen attribute, but the Screen also needs to have seats and type.  

8. Give a difference between composition and aggregation?  
**Answer:** In composition an object is a part of another object - the first can only exist within the second. In aggregation, the objects within an object are created independently.  

9. What is/are the advantage(s) of using composition/aggregation?  
**Answer:** They can be less messy than inheritance and you aren't limited to only one class like with inheritance.  

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?  
**Answer:** They are also destroyed.  

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?  
**Answer:** They exist independently.