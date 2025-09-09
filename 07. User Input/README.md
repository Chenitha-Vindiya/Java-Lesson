# Taking User Input with Scanner Library

## 📘 Concept
In Java, we use the **`Scanner` class** to take input from the user.  
The `Scanner` class is in the package **`java.util`**, so we must **import** it before use.

---

## 1️⃣ Importing Scanner
```java
import java.util.Scanner;

public class xxxx { // Replace xxx with your name
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in); // creating a scanner object

        input.close(); // close scanner
    }
}
```
## 2️⃣ Getting Input for Different Data Types

| Data Type              | Method                                                    | Example Code                        |
| ---------------------- | --------------------------------------------------------- | ----------------------------------- |
| `int`                  | `nextInt()`                                               | `int age = input.nextInt();`           |
| `float`                | `nextFloat()`                                             | `float price = input.nextFloat();`     |
| `double`               | `nextDouble()`                                            | `double pi = input.nextDouble();`      |
| `boolean`              | `nextBoolean()`                                           | `boolean flag = input.nextBoolean();`  |
| `String` (single word) | `next()`                                                  | `String name = input.next();`          |
| `String` (full line)   | `nextLine()`                                              | `String sentence = input.nextLine();`  |
| `char`                 | no direct method → read string, then take first character | `char grade = input.next().charAt(0);` |

## 3️⃣ Example Program
```java
import java.util.Scanner;

public class UserInputExample {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Taking different types of input
        System.out.print("Enter your name: ");
        String name = input.nextLine();

        System.out.print("Enter your age: ");
        int age = input.nextInt();

        System.out.print("Enter your GPA: ");
        float gpa = input.nextFloat();

        System.out.print("Enter your grade (A/B/C): ");
        char grade = input.next().charAt(0);

        System.out.print("Is Java fun? (true/false): ");
        boolean isJavaFun = input.nextBoolean();

        // Output
        System.out.println("\n--- User Details ---");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("GPA: " + gpa);
        System.out.println("Grade: " + grade);
        System.out.println("Is Java Fun? " + isJavaFun);

        input.close(); // close inputanner
    }
}
```

---

## 📝 Exercises

### Q1: Your Profile
- Ask the user for:
  - Name (String)
  - Age (int)
  - Height (float)
- Print them in one line:  
  `"My name is ___, I am ___ years old, and my height is ___ meters."`

---

### Q2: Simple Math
- Ask the user for **two integers**.  
- Print their **sum, difference**.  

Example output (if inputs are 8 and 4):
`Sum = 12`
`Difference = 4`

---

### Q3: Double It
- Ask the user to enter a **number**.  
- Print the number multiplied by 2.  

---

### Q4: Favorite Things
- Ask the user for:
  - Favorite color (String)  
  - Favorite food (String)  
- Print:  
  `"Your favorite color is ___ and your favorite food is ___."`

---

### Q5: Rectangle Area
- Ask the user for:
  - Length (int)  
  - Width (int)  
- Print the **area of the rectangle**.

---

### Q6: Circle Area
- Ask the user for the **radius (double)**.  
- Print the **area of the circle** using formula:  
  `area = 3.14 * radius * radius`

---

### Q7: Character Input
- Ask the user to enter a **single character** (char).  
- Print `"You entered: ___"`.  

