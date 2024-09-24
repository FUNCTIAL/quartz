---
tags:
  - Programming
created on: 2024-09-22
---

Object Oriented Programming is a kind of [[Programming Paradigms|programming paradigm]] based on the concept of **Object**.

## Objects
Objects are things with attributes and behaviors (methods) assigned to them. Subclass (attributes and behaviors) can be shared between many objects while not being exactly the same with classes.

Class: Animal → Objects: Human, Monkey

Objects can be created using Constructor

```java
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj1 = new Main();  // Create Object 1 of class main (constuctor)
    Main myObj2 = new Main();  // Object 2
    System.out.println(myObj1.x);
    System.out.println(myObj2.x);
  }
}
```

---
# References
1. [[ITCT241]]
2. [Java Constructors](https://www.w3schools.com/java/java_constructors.asp)