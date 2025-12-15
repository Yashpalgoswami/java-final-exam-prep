# Java Final Exam Preparation Quiz 📚

A comprehensive study guide with 100+ practice problems covering all core Java concepts for your final exam.

## 🎯 Overview

This repository is organized into 9 sections covering all the mastered concepts you need for your Java final exam. Each section includes practice problems, detailed explanations, and runnable code.

## 📖 Table of Contents

1. [Core Syntax](#01-core-syntax) - Variables, type casting, operators
2. [Strings & Logic](#02-strings-and-logic) - String operations, if statements, switches
3. [Loops](#03-loops) - For loops, while loops, conversions
4. [Methods](#04-methods) - Creating methods, parameters, pass by value/reference
5. [Arrays](#05-arrays) - 1D, 2D, and multidimensional arrays
6. [Recursion](#06-recursion) - Base cases, recursive cases, loop conversions
7. [Sorting & Searching](#07-sorting-searching) - All algorithms with Big O analysis
8. [Debugging Practice](#08-debugging-practice) - Syntactic, runtime, and logical errors
9. [Practice Exams](#09-practice-exam) - Two complete 45-minute timed exams

## ⏱️ Time Recommendations

- **Core Syntax**: 2 hours
- **Strings & Logic**: 2.5 hours
- **Loops**: 2 hours
- **Methods**: 2.5 hours
- **Arrays**: 3 hours
- **Recursion**: 3 hours
- **Sorting & Searching**: 3 hours
- **Debugging Practice**: 2 hours
- **Practice Exam 1**: 45 minutes
- **Practice Exam 2**: 45 minutes

**Total Study Time**: ~20 hours

## 🚀 How to Use This Repository

1. **Clone the repository**: `git clone https://github.com/Yashpalgoswami/java-final-exam-prep.git`
2. **Start with weaker areas** - Review the topics you find most challenging first
3. **Work through problems systematically** - Don't skip the "easy" ones
4. **Compile and run each file** - Make sure you understand the output
5. **Take the practice exams** - Simulate real exam conditions (45 minutes, open book)

## 📚 Quick Reference

### Common Operators
```java
+  // Addition
-  // Subtraction
*  // Multiplication
/  // Division (integer division for ints)
%  // Modulo (remainder)
++ // Increment
-- // Decrement
```

### String Methods
```java
.length()           // Returns length of string
.charAt(int)        // Returns character at index
.substring(int)     // Returns substring from index
.substring(int,int) // Returns substring between indices
.indexOf(String)    // Returns index of first occurrence
.equals(String)     // Compares strings (use this, not ==)
.toLowerCase()      // Converts to lowercase
.toUpperCase()      // Converts to uppercase
```

### Math Methods
```java
Math.pow(base, exp)  // Returns base^exp
Math.sqrt(num)       // Returns square root
Math.abs(num)        // Returns absolute value
Math.max(a, b)       // Returns larger value
Math.min(a, b)       // Returns smaller value
Math.random()        // Returns random 0.0-1.0
```

### Scanner Methods
```java
Scanner sc = new Scanner(System.in);
sc.nextInt()      // Reads int
sc.nextDouble()   // Reads double
sc.next()         // Reads one word
sc.nextLine()     // Reads entire line
sc.nextBoolean()  // Reads boolean
```

### Escape Characters
```java
\n  // Newline
\t  // Tab
\\  // Backslash
\"  // Double quote
\'  // Single quote
```

## 🔢 Number Systems Reference

### Binary (Base 2)
- Uses digits: 0, 1
- Example: `1010` = 10 in decimal

### Hexadecimal (Base 16)
- Uses digits: 0-9, A-F
- Example: `0xFF` = 255 in decimal
- Often prefixed with `0x` in code

*Note: You won't need to do conversions, but should recognize these formats*

## ⚡ Big O Complexity Cheat Sheet

Understanding algorithm efficiency:

```
O(log N) < O(N) < O(N²)
  ↑         ↑       ↑
Fastest   Medium  Slowest
```

### Search Algorithms
- **Linear Search**: O(N) - works on any array
- **Binary Search**: O(log N) - requires sorted array

### Sort Algorithms
- **Bubble Sort**: O(N²) worst case
- **Selection Sort**: O(N²) worst case
- **Insertion Sort**: O(N²) worst case
- **TimSort** (Java default): O(N log N) average case

## 💡 Study Tips

1. **Redo your labs** - Early labs should feel much easier now
2. **Practice debugging** - Fix broken code from incomplete assignments
3. **Attempt previous midterms** - Time yourself (45 minutes)
4. **Know your libraries** - Memorize common methods from String, Math, Scanner
5. **Understand recursion deeply** - Base cases and recursive cases
6. **Master array traversal** - Especially 2D arrays

## 🎓 Exam Day Reminders

- ✅ You can use this repository during the exam (open book)
- ✅ Know where to find documentation quickly
- ✅ Practice time management (don't spend too long on one problem)
- ✅ Test your code as you write it
- ✅ Check for edge cases

## 📖 External Resources

- [Oracle Java Documentation](https://docs.oracle.com/en/java/)
- [Java String API](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/String.html)
- [Java Math API](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/lang/Math.html)
- [Java Scanner API](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Scanner.html)
- [Java Arrays API](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/Arrays.html)

---

**Good luck on your final exam! 🎉**

*"I enjoy programming, and hope that you all do too, or will in time."* - Paul

---

## 📝 Progress Tracker

Mark off sections as you complete them:

- [ ] 01 - Core Syntax
- [ ] 02 - Strings & Logic
- [ ] 03 - Loops
- [ ] 04 - Methods
- [ ] 05 - Arrays
- [ ] 06 - Recursion
- [ ] 07 - Sorting & Searching
- [ ] 08 - Debugging Practice
- [ ] 09 - Practice Exam 1
- [ ] 09 - Practice Exam 2