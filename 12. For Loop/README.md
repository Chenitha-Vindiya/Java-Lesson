# For Loop

This lesson covers the **for loop** in Java, which is commonly used when the **number of iterations is known in advance**.

---

## 📘 Concept

- The **for loop** is a control flow statement that allows you to repeat a block of code a specific number of times.
- Syntax:

```java
for (initialization; condition; update) {
    // Code to execute
}
```
- Initialization → executed once at the start.
- Condition → checked before each iteration; if false, the loop ends.
- Update → executed after each iteration.

---

## 🖥️ Example 1 – Print Numbers 1 to 5

```java
public class ForExample {
    public static void main(String[] args) {

        for (int i = 1; i <= 5; i++) {
            System.out.println(i);
        }

    }
}
```

### Output:

<pre>
1
2
3
4
5
</pre>

---

## Example 2 – Sum of Numbers from 1 to 10

```java
public class SumFor {
    public static void main(String[] args) {
        int sum = 0;

        for (int i = 1; i <= 10; i++) {
            sum += i;
        }

        System.out.println("Sum = " + sum);
    }
}
```

### Output:

<pre>Sum = 55</pre>

---

## Example 3 – Multiplication Table

```java
import java.util.Scanner;

public class MultiplicationTable {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int num = input.nextInt();

        for (int i = 1; i <= 5; i++) {
            System.out.println(num + " x " + i + " = " + (num * i));
        }

        input.close();
    }
}

```

### Output (if input is 5):

<pre>
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 × 5 = 25
</pre>

---

## 📝 Key Points

| Feature        | Description                                 |
| -------------- | ------------------------------------------- |
| Initialization | Runs once at the start of the loop          |
| Condition      | Checked before each iteration               |
| Update         | Runs after each iteration                   |
| Use case       | Best when the number of iterations is known |

---

## 📝 Exercises

⚠️ Do not use `break`, `continue`, or `return`. Only use the **for loop** structure.

---

### 1️⃣ Print Numbers
- Write a program to **print numbers from 1 to 10** using a for loop.

---

## 2️⃣ Even Numbers
- Write a program to **print all even numbers between 1 and 50** using a for loop.

---

## 3️⃣ Sum of Numbers
- Write a program to **calculate the sum of numbers from 1 to N**, where `N` is entered by the user.

---

## 4️⃣ Multiplication Table
- Write a program to print the **multiplication table of a number** entered by the user.

---

## 5️⃣ Factorial
- Write a program to **find the factorial of a number** entered by the user using a for loop.  
  Example: Input = `5` → Output = `120`.

---

## 6️⃣ Sum of Odd Numbers
- Write a program to **find the sum of all odd numbers from 1 to 100**.

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
