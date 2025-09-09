# Switch Case Statement

This lesson covers the **switch-case statement** in Java, which is used to perform **multiple selection operations** based on the value of a variable.

---

## 📘 Concept

- The `switch` statement evaluates an expression and executes the corresponding `case` block that matches the value.
- Each `case` should end with a `break` statement. is used to exit the switch after executing a matching case. Without break, the program will `fall through` to the next case(s).
- `default` is executed if **none of the cases match**.

```java
switch(expression) {
    case value1:
        // code to execute
        break;
    case value2:
        // code to execute
        break;
    //...
    default:
        // code to execute if no case matches
}
```

## 📝 Exercises

### 1️⃣ Day of the Week
- Write a program that **prints the day name** (Monday–Sunday) based on a number (1–7) entered by the user.  
- If the number is not between 1–7, print “Invalid day”.

---

### 2️⃣ Simple Calculator
- Write a program that asks the user to **enter two numbers** and an **operator** (`+`, `-`, `*`, `/`).  
- Use a switch-case to perform the calculation and print the result.  
- If the operator is invalid, print “Invalid operator”.

---

### 3️⃣ Month Name
- Write a program that **prints the month name** (January–December) based on a number (1–12) entered by the user.  
- If the number is not in this range, print “Invalid month”.

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

