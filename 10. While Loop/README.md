# While Loop

This lesson covers the **while loop** in Java, which is used to execute a block of code **repeatedly as long as a condition is true**.

---

## 📘 Concept

- A `while` loop checks the **condition first** before executing the loop body.  
- If the condition is true, the loop body executes; if false, the loop stops.  
- Syntax:

```java
while (condition) {
    // Code to execute
}
```

---

## 🖥️ Example Programs – Print Numbers 1 to 5

```java
public class WhileExample {
    public static void main(String[] args) {

        int i = 1;

        while (i <= 5) {
            System.out.println(i);
            i++; // Increment to avoid infinite loop
        }

    }
}
```
### Output
<pre>
1
2
3
4
5
</pre>

---

## 🖥️ Example 2 – Sum of Numbers Entered by User

```java
import java.util.Scanner;

public class SumWhile {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        int sum = 0, num;
        System.out.println("Enter numbers to sum (0 to stop):");
        num = input.nextInt();

        while (num != 0) {   // Loop until user enters 0
            sum += num;
            num = input.nextInt();
        }

        System.out.println("Total sum: " + sum);
        input.close();
    }
}
```

---

## 📝 Key Points


| Feature          | Description                                           |
| ---------------- | ----------------------------------------------------- |
| Condition        | Checked **before each iteration**                     |
| Execution        | Loop runs **only if condition is true**               |
| Infinite loop    | If condition never becomes false, the loop never ends |
| Increment/Update | Must update variables inside loop to eventually stop  |

---

## 📝 Exercises

### 1️⃣ Print Numbers
- Write a program to **print numbers from 1 to 10** using a while loop.

---

### 2️⃣ Sum of Numbers
- Write a program to **calculate the sum of numbers from 1 to 50** using a while loop.

---

### 3️⃣ User Input Sum
- Write a program that **keeps asking the user to enter numbers until they enter 0**.  
- Print the **sum of all entered numbers**.

---

### 4️⃣ Print Even Numbers
- Write a program to **print all even numbers between 1 and 20** using a while loop.

---

### 5️⃣ Factorial Calculation
- Write a program to **calculate the factorial of a number entered by the user** using a while loop.
<pre>
example:
    !5 = 1 × 2 × 3 × 4 × 5 = 120
    !6 = 1 × 2 × 3 × 4 × 5 × 6 = 720
</pre>

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

