# `break`, `continue`, and `return` Statements

In Java, these control statements are used to change the normal flow of execution inside loops or methods.

---

## 1️⃣ `break` Statement

- Used to **terminate** a `loop` or a `switch` statement immediately.
- Control jumps to the first line **after the loop/switch**.

**Syntax:**
```java
break;
```
### Example:

```java
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        break; // Exit loop when i = 3
    }
    System.out.println(i);
}

System.out.println("Loop ended");
```

#### Output:
<pre>
1
2
Loop ended
</pre>

---

## 2️⃣ `Continue` Statement

- **Used to skip the current iteration** of the loop.
- Control jumps to the next iteration of the loop.

**Syntax:**
```java
continue;
```

### Example:

```java
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        continue; // Skip printing 3
    }
    System.out.println(i);
}
```

#### Output:
<pre>
1
2 
4 
5
</pre>

---

## 3️⃣ `Return` Statement

- Used to exit from a method `immediately`.
- Can also return a value (if the method has a return type).

**Syntax:**
```java
return;       // for void methods
```
### Example (void method):

```java
for (int i = 1; i <= 5; i++) {
	if (i == 3) {
		return; // Exit from main() completely
	}
	System.out.println(i);
}

System.out.println("This will not run");
```

#### Output:

<pre>
1
2
</pre>

---

## 📝 Key Differences

| Feature          | `break`                          | `continue`                       | `return`                    |
| ---------------- | -------------------------------- | -------------------------------- | --------------------------- |
| **Scope**        | Exits **nearest loop/switch**    | Skips **current iteration only** | Exits the **entire method** |
| **Where used**   | Loops & `switch`                 | Loops only                       | Any method                  |
| **After effect** | Program continues **after loop** | Program continues **next loop**  | Method execution ends       |


---

## 📝 Exercises

### 1️⃣ Break – Stop Loop Early
- Write a program to print numbers from 1 to 10.  
- Use `break` to **stop the loop when the number reaches 6**.  

---

### 2️⃣ Break – Stop at Negative Input
- Ask the user to enter numbers continuously.  
- Stop reading inputs when the user enters a **negative number** (use `break`).  

---

### 3️⃣ Continue – Skip Even Numbers
- Write a program to print numbers from 1 to 20.  
- Use `continue` to **skip even numbers**, printing only the odd numbers.  

---

### 4️⃣ Continue – Skip Multiples of 5
- Write a program to print numbers from 1 to 30.  
- Use `continue` to **skip numbers that are divisible by 5**.  

---

### 5️⃣ Return – Simple Input Validation
- Ask the user to enter a number.  
- If the number is negative, **use `return` to stop the program** with a message: `"Negative numbers not allowed"`.  
- Otherwise, print `"Number accepted"`.  

---

### 6️⃣ Return – Voting Eligibility
- Ask the user to enter their age.  
- If age < 18, **use `return` to stop the program** and print `"Not eligible to vote"`.  
- If age ≥ 18, print `"Eligible to vote"`.  

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
