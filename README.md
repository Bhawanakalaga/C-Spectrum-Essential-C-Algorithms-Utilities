# C Spectrum: Essential C Algorithms & Utilities

A broad-spectrum collection of C programs demonstrating core procedural techniques—from basic I/O and control flow through data structures, algorithms, and file handling.

---

## 📂 Contents

| Program      | Filename                   | Description                                                   |
|:------------:|:---------------------------|:--------------------------------------------------------------|
| Calculator   | `simple_calculator.c`      | Basic arithmetic (`+ - * / %`) with input validation.         |
| Quadratic    | `quadratic_roots.c`        | Solves ax²+bx+c=0, handling real, repeated, and complex roots.|
| Electricity  | `electricity_bill.c`       | Slab-rate billing with minimum charge and surcharge logic.    |
| Pyramid      | `number_pyramid.c`         | Prints a centered numeric pyramid of configurable height.     |
| BinarySearch | `binary_search.c`          | O(log n) search on a sorted integer array.                    |
| MatrixMul    | `matrix_multiplication.c`  | Validates dimensions and multiplies two matrices.             |
| TaylorTan    | `taylor_tan.c`             | Approximates sin/cos via Taylor series, compares tan(x).      |
| BubbleSort   | `bubble_sort.c`            | Optimized bubble sort with early-exit on sorted input.        |
| StringOps    | `string_ops.c`             | Custom `strlen`, `strcmp`, and `strcat` implementations.      |
| StudentMarks | `student_marks.c`          | Uses `struct` to compute average marks and list deviations.   |
| Statistics   | `statistics_pointers.c`    | Sum, mean, and standard deviation using pointer arithmetic.   |
| FileCopy     | `file_copy.c`              | Character-by-character text-file copy with error checks.      |

---

## ⚙️ Prerequisites

- A C compiler supporting C99 or later (e.g. `gcc`, `clang`).  
- Standard headers: `<stdio.h>`, `<stdlib.h>`, `<string.h>`, `<math.h>`, etc.

---

## 🚀 Build & Run

Compile any single program like:

```bash
gcc -std=c11 -Wall simple_calculator.c -o simple_calculator
./simple_calculator
