# Core Syntax 🔤

Master the fundamental building blocks of Java programming.

## 📚 Learning Objectives

By completing this section, you will:
- Understand how to properly declare and initialize variables
- Master type casting between different data types
- Use all common operators correctly
- Know Java naming conventions and syntax rules

## ⏱️ Estimated Time: 2 hours

## 📝 Files in This Section

1. **VariableDeclaration.java** (30 min)
   - Declaring different data types
   - Variable naming rules
   - Allowable vs non-allowable names

2. **TypeCasting.java** (45 min)
   - Implicit and explicit casting
   - Converting between types
   - Working with char arithmetic

3. **Operators.java** (45 min)
   - Arithmetic operators
   - Operator precedence
   - Modulo and increment/decrement

## 🎯 Key Concepts

### Data Types
- **int**: Whole numbers (-2,147,483,648 to 2,147,483,647)
- **double**: Decimal numbers (64-bit floating point)
- **char**: Single character (uses single quotes: 'A')
- **boolean**: true or false
- **String**: Text (uses double quotes: "Hello")

### Variable Naming Rules
✅ **Allowed**:
- Start with letter, underscore, or $
- Contain letters, numbers, underscores
- Use camelCase convention
- Examples: `myVariable`, `count2`, `_temp`, `$price`

❌ **Not Allowed**:
- Start with a number
- Use reserved keywords (int, class, public, etc.)
- Contain spaces or special characters (except _ and $)
- Examples: `2count`, `my-variable`, `class`

### Comments
```java
// Single-line comment

/* Multi-line
   comment */

/** JavaDoc comment
  * for documentation */
```

### Where to Put Curly Braces {}
```java
public class MyClass {  // Class braces
    public static void main(String[] args) {  // Method braces
        if (condition) {  // Control structure braces
            // code here
        }
    }
}
```

## 🔗 Oracle Documentation
- [Primitive Data Types](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
- [Variables](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/variables.html)
- [Operators](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/operators.html)

## ⚠️ Common Mistakes

1. **Using == to compare Strings** - Use `.equals()` instead
2. **Forgetting semicolons** - Every statement needs one
3. **Integer division** - `5 / 2` equals `2`, not `2.5`
4. **Declaring variables inside wrong scope** - Variables declared in {} only exist there
5. **Using reserved keywords** - Can't name variables `int`, `class`, etc.

## ✅ Checklist

After completing this section, you should be able to:
- [ ] Declare variables of all primitive types
- [ ] Understand implicit vs explicit casting
- [ ] Use all arithmetic operators correctly
- [ ] Apply operator precedence rules
- [ ] Name variables following Java conventions
- [ ] Write proper comments

---

**Ready? Start with `VariableDeclaration.java`!**