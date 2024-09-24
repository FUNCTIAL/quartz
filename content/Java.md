---
tags:
  - Programming
created on: 2024-09-22
---

Java is a [[Object Oriented Programming]] Language

## Variables in Java
[[Variables|Variables]] in Java split in two data types, where primitive data types are predefined while non-primitive types are created

1. Primitive data type
	1. byte
	2. short
	3. int
	4. long
	5. float
	6. double
	7. boolean
	8. char
2. Non-primitive data type
	- String
	- Arrays
	- Classes
	- Interface

To convert higher rank primitive data types to lower rank in Java use the cast operator, but be aware that cast discard fractional part of the variables
```Java
double balance = total + tax;
int dollars = (int) balance;
```

![[Pasted image 20240922144614.png]]

As a solution, we can use `Math.round` to convert the floating-point number into nearest integer
```java
long rounded = Math.round(balance);

// balance = 13.5 -> rounded = 14
// balance = 13.49 -> rounded = 13
```

### Reference Data Type


---
# References
1. [[ITCT241]]
2. [Java Data Types](https://www.w3schools.com/java/java_data_types.asp)
3. [Java Non-Primitive Data Types](https://www.w3schools.com/java/java_data_types_non-prim.asp)
4. [Java Constructors](https://www.w3schools.com/java/java_constructors.asp)