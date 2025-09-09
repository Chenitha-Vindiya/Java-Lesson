# Assignment Operator & Increment/Decrement

## 📘 Concept

### 1️⃣ Assignment Operators
Assignment operators are used to **assign values** to variables.

| Operator | Meaning                     | Example            | Equivalent To   |
|----------|----------------------------|-------------------|----------------|
| `=`      | Assign                     | `x = 5`           | `x = 5`        |
| `+=`     | Add and assign             | `x += 3`          | `x = x + 3`    |
| `-=`     | Subtract and assign        | `x -= 2`          | `x = x - 2`    |
| `*=`     | Multiply and assign        | `x *= 4`          | `x = x * 4`    |
| `/=`     | Divide and assign          | `x /= 2`          | `x = x / 2`    |
| `%=`     | Modulus and assign         | `x %= 3`          | `x = x % 3`    |

---

### 2️⃣ Increment & Decrement Operators
These are **unary operators** used to increase or decrease a value by 1.

#### Increment
| Operator | Type       | Example | Explanation                  |
|----------|-----------|---------|------------------------------|
| `++x`    | Pre-increment  | `x = 5; ++x;` → 6 | Increases first, then uses the value |
| `x++`    | Post-increment | `x = 5; x++;` → 5 | Uses the value, then increases |

#### Decrement
| Operator | Type       | Example | Explanation                  |
|----------|-----------|---------|------------------------------|
| `--x`    | Pre-decrement  | `x = 5; --x;` → 4 | Decreases first, then uses the value |
| `x--`    | Post-decrement | `x = 5; x--;` → 5 | Uses the value, then decreases |

---

## 🖥️ Examples

```java
public class xxxx { // Replace xxxx with your name
    public static void main(String[] args) {
        int x = 10;

        // Assignment operators
        x += 5;  // x = 15
        x -= 3;  // x = 12
        x *= 2;  // x = 24
        x /= 4;  // x = 6
        x %= 4;  // x = 2

        System.out.println("After assignment operations, x = " + x);

        // Increment and Decrement
        int a = 5;
        System.out.println("a = " + a);       // 5
        System.out.println("++a = " + ++a);   // 6 (pre-increment)
        System.out.println("a++ = " + a++);   // 6 (post-increment, then a=7)
        System.out.println("a = " + a);       // 7

        int b = 5;
        System.out.println("--b = " + --b);   // 4 (pre-decrement)
        System.out.println("b-- = " + b--);   // 4 (post-decrement, then b=3)
        System.out.println("b = " + b);       // 3
    }
}

