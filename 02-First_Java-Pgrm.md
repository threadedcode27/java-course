# 📘 Java Programming

# Lecture 2 – Writing Your First Java Program

---

# 1. Introduction

In the previous lecture, we learned about Java, its features, JDK, JRE, and JVM.

Before writing our first Java program, we should understand:

- Java Naming Conventions
- Rules for Writing a Java Program
- Basic Structure (Syntax) of a Java Program
- Hello World Program

Let's learn each of these step by step.

---

# 2. Java Naming Conventions

A **Naming Convention** is a set of rules followed while naming classes, methods, variables, and constants.

Following naming conventions makes the code easier to read, understand, and maintain.

---

## 2.1 Class Naming Convention (Pascal Case)

Java class names should follow **Pascal Case**.

### What is Pascal Case?

In Pascal Case, the **first letter of every word is capitalized**, and there are **no spaces** between words.

### Examples

```text
Student
BankAccount
EmployeeManagement
CollegeManagementSystem
```

### Rules

- Class name should start with a letter.
- It can also start with `_` or `$` (not recommended).
- It cannot start with a number.
- It cannot contain spaces.
- Java keywords cannot be used as class names.
- Use meaningful names.

---

## 2.2 Method Naming Convention (camelCase)

Method names should follow **camelCase**.

### What is camelCase?

In camelCase, the **first word starts with a lowercase letter**, and the **first letter of every subsequent word is capitalized**.

### Examples

```text
display()
calculateArea()
printStudentDetails()
findMaximum()
```

### Rules

- Start with a lowercase letter.
- Use meaningful names.
- Do not use spaces.
- Use verbs whenever possible because methods represent actions.

---

## 2.3 Variable Naming Convention (camelCase)

Variables also follow **camelCase**.

### Examples

```text
studentName
totalMarks
mobileNumber
age
```

### Rules

- Start with a lowercase letter.
- Use meaningful names.
- Avoid single-letter variable names unless necessary.

---

## 2.4 Constant Naming Convention (UPPER_SNAKE_CASE)

Constants are written using **UPPER_SNAKE_CASE**.

### Examples

```text
MAX_SIZE
PI
MIN_AGE
DEFAULT_TIMEOUT
```

---

# 3. Rules for Writing a Java Program

Before writing a Java program, remember the following rules:

- Every Java program must contain a class.
- The file name and public class name must be the same.
- Every statement ends with a semicolon (`;`).
- Java is case-sensitive.
- Curly braces `{}` define blocks of code.
- Every Java program starts execution from the `main()` method.

---

# 4. Basic Structure of a Java Program

Every Java program follows a basic structure.

```java
public class ClassName {

    public static void main(String[] args) {

    }

}
```

This is the minimum structure required to write a Java program.

---

# 5. Understanding the Program Structure

Let's understand each part of the program.

---

## 5.1 public

`public` is an **access modifier**.

An access modifier specifies **where a class or method can be accessed**.

### Types of Access Modifiers

| Access Modifier | Description |
|-----------------|-------------|
| **public** | Can be accessed from anywhere in the program. |
| **private** | Can be accessed only within the same class. |
| **protected** | Can be accessed within the same package and by subclasses (Inheritance). |

> **Note:** We will study access modifiers in detail later.

---

## 5.2 class

The `class` keyword is used to create a **class**.

A class acts as a **blueprint** for creating objects.

Example:

```java
public class Student
```

Here,

- `public` → Access Modifier
- `class` → Keyword
- `Student` → Class Name

---

## 5.3 Class Name

The class name identifies the Java class.

Examples

```text
Student
Employee
Calculator
BankAccount
```

**Important Rule**

The **class name** and the **file name** must be exactly the same.

Example

```text
Student.java
```

```java
public class Student
```

---

## 5.4 public static void main(String[] args)

This is called the **main() method**.

The `main()` method is the **entry point** of every Java application.

Whenever a Java program is executed, the JVM first looks for the `main()` method.

Execution always begins from this method.

### Components of the main() Method

| Keyword | Meaning |
|----------|---------|
| `public` | Accessible from anywhere |
| `static` | Can be called without creating an object |
| `void` | Does not return any value |
| `main` | Method name where execution starts |
| `String[] args` | Stores command-line arguments |

> We will study each keyword in detail in upcoming lectures.

---

## 5.5 System.out.println()

`System.out.println()` is used to display output on the console.

### Syntax

```java
System.out.println("Message");
```

### Example

```java
System.out.println("Welcome to Java");
```

### Output

```text
Welcome to Java
```

---

# 6. Hello World Program

Now let's write our first Java program.

```java
public class HelloWorld {

    public static void main(String[] args) {

        System.out.println("Hello, World!");

    }

}
```

---

# 7. Output

```text
Hello, World!
```

---

# 8. Program Explanation

```java
public class HelloWorld {
```

Creates a public class named **HelloWorld**.

---

```java
public static void main(String[] args) {
```

Defines the **main() method**, where the execution of the program begins.

---

```java
System.out.println("Hello, World!");
```

Prints **Hello, World!** on the console.

---

```java
}
```

Closes the `main()` method.

---

```java
}
```

Closes the class.

---

# 9. Important Points

- Java is case-sensitive.
- Every Java program must contain a class.
- The class name and file name must be the same.
- Every statement ends with a semicolon (`;`).
- Execution always starts from the `main()` method.
- `System.out.println()` is used to display output.

---

# 10. Common Mistakes

❌ Forgetting the semicolon (`;`)

❌ Using a different file name and class name

❌ Misspelling `main()`

❌ Misspelling `System.out.println()`

❌ Forgetting curly braces `{}`

❌ Writing Java keywords with incorrect capitalization

---

# 11. Summary

In this lecture, we learned:

- Java Naming Conventions
- Pascal Case
- camelCase
- UPPER_SNAKE_CASE
- Rules for Writing Java Programs
- Basic Structure of a Java Program
- Access Modifiers
- Class
- main() Method
- System.out.println()
- Hello World Program

---

# 12. Theory Questions

1. What is a naming convention?
2. What is Pascal Case? Give two examples.
3. What is camelCase? Give two examples.
4. What are the rules for naming a Java class?
5. What is an access modifier?
6. Explain the three types of access modifiers.
7. What is the purpose of the `main()` method?
8. Why should the class name and file name be the same?
9. What is the use of `System.out.println()`?
10. Why is Java called a case-sensitive language?

---

# 13. Practical Questions

### 1. Write a Java program to print your name.

### 2. Write a Java program to print your college name.

### 3. Write a Java program to print three different messages using `System.out.println()`.

### Sample Output

```text
Name    : Anusha
College : NIE Mysore
Course  : Information Science and Engineering
```
