# Selection Statements

This project contains examples and exercises to help beginners understand **selection statements** in Java. Selection statements allow programs to make decisions based on conditions.

---

## 📘 Concept

### 1️⃣ If Statement
Executes a block of code **only if a condition is true**.

```java
if (condition) {
    // code to execute if condition is true
}
```
### 2️⃣ If-Else Statement
Executes one block **if the condition is true**, and another **if it is false.**

```java
if (condition) {
    // code if true
} else {
    // code if false
}
```
### 3️⃣ Else-If Ladder
Checks multiple conditions in sequence.

```java
if (condition1) {
    // code for condition1
} else if (condition2) {
    // code for condition2
} else {
    // code if none are true
}
```
### 4️⃣ Shorthand If-Else (Ternary Operator)
A **compact way to write an if-else statement** in a single line.

```java
result = (condition) ? valueIfTrue : valueIfFalse;
```

---

### 🖥️ Example Program
```java
public class SelectionExample {
    public static void main(String[] args) {
        int num = 10;

        // If statement
        if (num > 0) {
            System.out.println(num + " is positive");
        }

        // If-Else statement
        if (num % 2 == 0) {
            System.out.println(num + " is even");
        } else {
            System.out.println(num + " is odd");
        }

        // Shorthand If-Else (Ternary)
        String result = (num > 0) ? "Positive" : "Negative";
        System.out.println("Number is " + result);
    }
}
```

---

## 📝 Exercises

### 1️⃣ If Statement
- Write a program to check if a number entered by the user is **positive**.  

---

### 2️⃣ If-Else Statement
- Write a program to check if a number entered by the user is **even or odd**.  

---

### 3️⃣ Else-If Statement
- Write a program to assign **grades** based on marks entered by the user:  
  - Marks ≥ 75 → "A"  
  - Marks ≥ 65 → "B"  
  - Marks ≥ 55 → "C"  
  - Marks ≥ 35 → "S"
  - Marks < 35 → "W"

---

### 4️⃣ Shorthand If-Else (Ternary Operator)
- Write a program to determine the **maximum of two numbers** entered by the user using a ternary operator.  

---

#### Reference 

```java
import java.util.Scanner;

public class xxxx { // Replace xxxx with your name
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        
    }
}
```

