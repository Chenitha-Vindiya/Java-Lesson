# Relational operators & Logical operators

## 📘 Concept

### 1️⃣ Relational Operators
Relational operators are used to **compare two values**.  
They return a **boolean value**: `true` or `false`.

| Operator | Meaning              | Example         | Output |
|----------|--------------------|----------------|--------|
| `==`     | Equal to            | `5 == 5`       | true   |
| `!=`     | Not equal to        | `5 != 3`       | true   |
| `>`      | Greater than        | `5 > 3`        | true   |
| `<`      | Less than           | `3 < 5`        | true   |
| `>=`     | Greater than or equal | `5 >= 5`     | true   |
| `<=`     | Less than or equal  | `3 <= 5`       | true   |

---

### 2️⃣ Logical Operators
Logical operators are used to **combine multiple boolean expressions**.  

| Operator | Meaning            | Example                   | Output |
|----------|------------------|---------------------------|--------|
| `&&`     | Logical AND       | `(5 > 3) && (2 < 4)`     | true   |
| `ll`     | Logical OR        | `(5 > 3) ll (2 > 4)`     | true   |
| `!`      | Logical NOT       | `!(5 > 3)`               | false  |
| `<<`     | Left Shift        | `5 << 3`                 | 40     |
| `>>`      | Right Shift      | `5 >> 3`                 | 0.625  |

---

## Q4

### Q4A: Relational Operators
1. Declare two integers `x = 10` and `y = 20`.  
   - Print whether `x` is greater than `y`.  
   - Print whether `x` is equal to `y`.  
   - Print whether `y` is less than or equal to `20`.  

---

### Q4B: Logical AND (&&)
Declare one integers `age = 10` and one boolean `citizen = true`. 
- Print the result of `age >= 18` **AND** `citizen == true`   

---

### Q4C: Logical OR (||)
Check if a student **passed** an exam:  
- A student passes if **marks >= 40 OR reExam = true**.  
- Test with `marks = 35` and `reExam = true`.  

---

### Q4D: Logical NOT (!)
Write a small program that:  
- Declares `boolean isRaining = false;`  
- Print the value of `!isRaining`.  

---

### Q5: Mixed Practice
Let `a = 5, b = 8, c = 5`. Predict and then print the outputs:  
```java
System.out.println((a == c) && (b > a));
System.out.println((a != b) || (c < b));
System.out.println(!(a > c));
```
---

### Reference 

```java
public class xxxx { // replace xxxx with your name
    public static void main(String[] args) {
        
    }
}
```

