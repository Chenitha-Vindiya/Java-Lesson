# Data Types & Variable Naming

## 📘 Concept
In Java, **every variable has a data type** that defines what kind of data it can store.  
This lesson covers the main data types and **variable naming rules**.

---

## 1️⃣ Data Types with Examples

| Category       | Data Type        | Example                        |
|----------------|----------------|--------------------------------|
| Integers       | `byte`          | `byte age = 25;`               |
|                | `short`         | `short s = 5000;`              |
|                | `int`           | `int i = 10000;`               |
|                | `long`          | `long l = 100000L;`            |
| Real Numbers   | `float`         | `float f = 3.14f;`             |
|                | `double`        | `double d = 3.14159;`          |
| Characters     | `char`          | `char grade = 'A';`            |
| Boolean        | `boolean`       | `boolean isJavaFun = true;`    |
| Strings        | `String`        | `String name = "Chenitha";`    |

---

## 2️⃣ Variable Naming Rules

1. **Must start with a letter, `$`, or `_`**  
   ```java
   int age;       // valid
   int _count;    // valid
   int $price;    // valid
   ```
2. **Cannot start with a number**
   ```java
   int 1number;   // invalid
   ```
3. **Cannot use Java keywords**
   ```java
   int class;     // invalid
   ```
4. **Case-sensitive**
   ```java
   int Age;       // different from int age;
   ```
4. **Use meaningful names**
   ```java
   int studentScore;  // better than int s;
   ```

