# Do-While Loop

This lesson covers the **do-while loop** in Java, which is similar to the `while` loop but with one important difference:  

The **do-while loop executes the block at least once**, even if the condition is false.

---

## 📘 Concept

- **Syntax:**

```java
int x = 0; // control varible

do {
    // Code to execute
    i++; // increment
} while (condition);
```

- In a `while loop`, the condition is checked before execution.

- In a `do-while loop`, the condition is checked after execution

---

## 🖥️ Example 1 - Print Numbers 1 to 5

```java
public class DoWhileExample1 {
    public static void main(String[] args) {
        int i = 1;

        do {
            System.out.println(i);
            i++;
        } while (i <= 5);
    }
}
```
- Output:
<pre>
1
2
3
4
5
</pre>

---

## 🖥️ Example 2 – At Least One Execution

```java
public class DoWhileExample2 {
    public static void main(String[] args) {
        int i = 10;

        do {
            System.out.println("This runs once even if condition is false");
            i++;
        } while (i < 5); // condition false, but loop body executed once
    }
}
```
- Output:
<pre>
This runs once even if condition is false
</pre>

---

## 📝 Key Points

| Feature         | `while` loop                     | `do-while` loop                       |
| --------------- | -------------------------------- | ------------------------------------- |
| Condition Check | Before execution                 | After execution                       |
| Guaranteed Run  | Not guaranteed (may run 0 times) | Runs at least once                    |
| Syntax End      | `}`                              | `} while (condition);` (note the `;`) |

---

## 📝 Exercises

⚠️ Do not use `break`, `continue`, or `return` in these solutions. Only use **do-while**.

---

### 1️⃣ Print Numbers
- Write a program to **print numbers from 1 to 10** using a do-while loop.

---

### 2️⃣ Multiplication Table
- Write a program to print the **multiplication table of a number** entered by the user.  
- Example: If user enters `5`, output should be like this
<pre>
5 × 1 = 5
5 × 2 = 10
5 × 3 = 15
5 × 4 = 20
5 × 5 = 25
</pre>

---

### 3️⃣ Sum of Natural Numbers
- Write a program to **calculate the sum of numbers from 1 to N**, where `N` is entered by the user.  
- Example: Input `N = 5` → Output = `15`.

---

### 4️⃣ Reverse Digits
- Write a program to **reverse the digits of a number** entered by the user.  
- Example: Input `1234` → Output = `4321`.

---

### 5️⃣ Digit Count
- Write a program to **count the number of digits** in a number entered by the user.  
- Example: Input `2456` → Output = `4`.

---

### 6️⃣ Guessing Game
- Write a program where the user must **guess a secret number** (predefined in the code).  
- Keep asking until the user enters the correct number.

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
