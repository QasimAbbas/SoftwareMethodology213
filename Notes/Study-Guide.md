# Software Methodology - Study Guide
## Midterm 1 - February 23, 2017

## Object Oriented Programming

### Constructor
* Used to create instances of a class (Objects)
* Method that is the same name as the class
  * Defauilt constructor is empty method initilzed
* Takes in parameters to initialze an object
 * Can take any amount/types
 * More than one constructor then does method matching based off of parameters

```java
public class Point{
 int x, y;
 public Point(int x, int y){
  this.x = x;
  this.y = y
 }
}

```

### Inheritance
* Different kinds of objects have a certain ammount common with each other
* Creating a subclass for a class




### Static and Dynamic Types
* Static: Type of object at compile time
 * types are associated by variables not values
* Dynamic: Object at Runtime
 * Do allow you to have type information, but doing
 
 
 ```java
 Ponint p3 = new ColoredPoint(2,e,"red");
 p3.toString is static call bound to dynamic type ColoredPoint
 `` 
