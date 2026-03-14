# java-test-0002-final-14953-akash
Final Project Assignment - This repository contains the complete final project code and documentation.

## Problem Statement

This assessment evaluates the candidate’s ability to implement **number-based patterns using nested loops in Java**. The candidate must create a program that correctly generates the required **mirrored number pyramid**.

The program should demonstrate proper use of loop control, logical number generation, and structured output formatting.

---

# Approach

1. **Define the number of rows**
   - Use a variable `n` to represent the height of the pyramid.

2. **Use nested loops**
   - The outer loop controls the rows.
   - Inner loops handle spacing and number printing.

3. **Print leading spaces**
   - For each row, print spaces to align the pyramid in the center.

4. **Print increasing numbers**
   - Print numbers from `1` to the current row number.

5. **Print decreasing numbers**
   - Print numbers from `(row - 1)` down to `1`.

6. **Move to the next row**
   - Print a newline after completing each row.

---

# Time Complexity

**O(n²)**

---

# Space Complexity

**O(1)**