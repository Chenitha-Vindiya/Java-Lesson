# Operator Precedence

## 📘 Concept
When an expression has more than one operator, **operator precedence** decides which operation happens first.  
If you want to control the order, use **parentheses `()`**.

### 🔹 Precedence Order (common operators)
1. `()` – Parentheses  
2. `* / %` – Multiplication, Division, Modulus  
3. `+ -` – Addition, Subtraction  
4. `=` – Assignment  

---

## 🗒️ Note: `print` vs `println`
- `System.out.print()` → Prints the text but cousor **does not move to a new line**.  
- `System.out.println()` → Prints the text and couser **moves to the next line**.  

## 🖥️ Q2

```java
public class xxxx { // replace xxxx with your name
    public static void main(String[] args) {
        
        // Q2A: Do multiplication before addition
        // Step 1: 5*2 = 10
        // Step 2: 10+10 = 20
        // do this in one line inside print command answer should be 20
        // change print command syntax as you need
        System.out.print('Answer for Q2A - ')
        System.out.print();

        // Q2B: Do addition before addition
        // note : Parentheses change the order
        // Step 1: 10+5 = 15
        // Step 2: 15*2 = 30
        // do this in one line inside print command answer should be 30
        // change print command syntax as you need
        System.out.print('Answer for Q2B - ')
        System.out.print();

        // Q2C: Division and multiplication (same precedence, left to right)
        // Step 1: 20/5 = 4
        // Step 2: 4*2 = 8
        // do this in one line inside print command answer should be 8
        // change print command syntax as you need
        System.out.print('Answer for Q2C - ')
        System.out.print();

        // Q2D: Use modules devision operator
        // Step 1: get reminder of 17/3 = 2 (reminder)
        // Step 2: 2+4 = 6
        // do this in one line inside print command answer should be 6
        // change print command syntax as you need
        System.out.print('Answer for Q2D - ')
        System.out.print();

        // Q2E: Use whatever operaters you want (at least 5 include Parentheses)
        // do this in one line inside print command answer should be 14
        // change print command syntax as you need
        System.out.print('Answer for Q2E - ')
        System.out.print();
    }
}
