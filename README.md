# Student Grade Tracker & Restaurant Management System
### Python Programming Fundamentals — BITS Pilani (MSc Data Science & AI)

This repository contains a two-part Python project demonstrating core programming proficiency, data structure manipulation, and algorithmic logic.

---

## 📂 Project Overview

### Part 1: Student Grade Tracker (Basics & Control Flow)
Focused on string manipulation, data normalization, and basic conditional logic.
* **Data Parsing:** Cleaned raw student strings using `.strip()` and `.title()`.
* **Grade Analysis:** Implemented a multi-tier grading system (A+ to F).
* **Statistics:** Calculated class-wide metrics including Topper identification and Average scores.
* **Input Validation:** Created a dynamic marks-entry system with error handling for non-numeric inputs.

### Part 2: Restaurant Order Management (Data Structures)
Focused on complex nested data structures (Lists and Dictionaries) and memory management.
* **Menu Exploration:** Grouped nested dictionary data by categories with formatted alignment.
* **Cart Operations:** Implemented CRUD (Create, Read, Update, Delete) logic for a shopping cart, preventing duplicate entries and validating item availability.
* **Inventory Tracking:** Simulated order fulfillment and deduction of stock levels.
* **Deep Copy Protection:** Explicitly demonstrated the use of `copy.deepcopy()` to maintain an independent system backup, protecting data from unintended references.
* **Sales Log Analysis:** Processed hierarchical JSON-like data to identify best-selling days and most frequent orders.

---

## 🛠️ Technical Skills Demonstrated

| Category | Specific Methods & Tools |
| :--- | :--- |
| **String Handling** | `split()`, `join()`, `count()`, `replace()`, `format()` |
| **Data Structures** | Nested Dictionaries, Lists of Tuples, Dictionary Comprehension |
| **Logic & Loops** | `while True`, `enumerate()`, `if-elif-else`, Lambda sorting |
| **Memory Management** | `copy.deepcopy()` for independent object cloning |
| **Reporting** | F-string padding/alignment for tabular console outputs |

---

## 🚀 Execution Instructions

1.  **Environment:** Ensure Python 3.8 or higher is installed.
2.  **Files:** Run the provided Jupyter Notebook (`.ipynb`) or Python script (`.py`).
3.  **Validation:** * Observe the **"✓ Valid name"** checks in Part 1.
    * Note the **"Deep Copy Proof"** in Part 2, showing that modifying the live inventory does not affect the backup.
    * View the **Reorder Alerts** triggered when stock falls below the threshold.

---

## 📊 Sample Output: Order Summary (Part 2)
```text
===================================
          Order Summary          
===================================
Paneer Tikka       x3    ₹ 540.00
-----------------------------------
Subtotal:                ₹ 540.00
GST (5%):                ₹  27.00
Total Payable:           ₹ 567.00
===================================


👤 Author
###Harshwardhan Srivastava *(Bitsom Assignment)*
