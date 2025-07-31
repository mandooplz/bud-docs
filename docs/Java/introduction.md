---
sidebar_position: 1
---

# Introduction to Java

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

## Basic Syntax

Here is a simple "Hello, World!" program in Java:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Variables and Data Types

```Java
// Declaring variables
int myNumber = 5;               // Integer
double myDouble = 5.99;         // Floating-point number
char myLetter = 'D';            // Character
boolean myBool = true;          // Boolean
String myText = "Hello";        // String
```

### Control Flow

```java
// If-else statement
if (myNumber > 0) {
    System.out.println("The number is positive.");
} else {
    System.out.println("The number is not positive.");
}

// For loop
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```
