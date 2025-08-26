Project "figures"
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 1.

This is a very simple project to demonstrate some characteristics of
objects.

You can create various shapes, and you will see, if you do, that those
shapes are drawn on screen (in a window that we call the "canvas").

You can then manipulate these objects: change their position, size and 
colour. Try it out: create a few different squares, triangles and circles.

This project is designed as a first example of object-oriented programming.
It illustrates a number of concepts:

 - a Java project (application) is a collection of classes
 - objects can be created from classes
 - from any one class, many objects may be created
 - objects have operations (methods)
 - operations can have parameters
 - parameters have types (at least String and int)
 - objects hold data (fields)
 - the operations and fields are common to all objects
 - the values stored in the fields can be different for each object

The project also demonstrates

 - BlueJ object creation
 - interactive method invocation
 - parameter passing

A good second project to look at after this is "picture", which adds a class
to those ones in this project. That class (named "Picture") uses the shapes
to draw a picture. It can be used to experiment with coding.




this is an edited part




************* ANSWERS TO THE QUESTIONS *************

Part 3 (Figures)
2. Q- What happens if you call moveDown twice?      A- It makes the object move downwards twice at a certain distance.
   Q- Or three times?     A- It moves thrice instead of twice
   Q- What happens if you call makeInvisible twice?     A- It just goes invisible

3. Q- Invoke the changeColor method, and write the color into the parameter field without the quotes. What happens?     A- It says Error: cannot find symbol -  variable blue

9. Q- While you are doing this, write down what you have to do to achieve this. Could it be done in different ways?     A- First step is to generate a canvas along with all the shapes needed. Second, you have to make all the added shapes visible to then manipulate their 
      movement with the void commands moveLeft(), moveRight(), moveUp() or moveDown(). You can also use moveVertical(int distance) or moveHorizontal(int distance) to move the shapes at a more desirable distance. Third, you have to change the colors of the added shapes
      by using void changeColor and typing out one of the supported colors in quotes into the parameter field. Now you have your desired art piece and yes it is possible to achieve this in different ways.
