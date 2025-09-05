# 📺 ft_printf-42

> **ft_printf-42** is a custom implementation of the standard C library's `printf` function, developed as part of the 42 School curriculum. This project delves into variadic functions, format specifiers, and formatted output, providing a deeper understanding of how `printf` operates under the hood.

---

## 📌 Project Overview

**ft_printf-42** aims to:

- Recreate the functionality of the standard `printf` function.
- Implement support for various format specifiers.
- Handle variadic arguments using `stdarg.h`.
- Manage typecasting and formatting for different data types.
- Enhance understanding of formatted output and memory management.

By undertaking this project, you will gain hands-on experience with:

- Parsing format strings.
- Handling variable argument lists.
- Implementing custom formatting logic.
- Managing memory efficiently.

---

## ✨ Features

- **Format Specifiers Support:**
  - `%c`: Character
  - `%s`: String
  - `%d` / `%i`: Signed decimal integer
  - `%u`: Unsigned decimal integer
  - `%x` / `%X`: Unsigned hexadecimal integer
  - `%p`: Pointer address
  - `%f`: Floating-point number

- **Flags and Modifiers:**
  - Width and precision specifiers.
  - Left and right alignment.
  - Zero-padding and space-padding.

- **Variadic Argument Handling:**
  - Utilizes `va_list`, `va_start`, `va_arg`, and `va_end` for processing variable arguments.

- **Recursive Algorithms:**
  - Implements recursion for number formatting in different bases (e.g., hexadecimal).

- **Error Handling:**
  - Robust error handling for invalid inputs and failed memory allocations.

- **Return Value:**
  - Returns the total number of characters printed, mimicking the behavior of the standard `printf` function.

---

## 🛠 Technologies Used

- **Programming Language:** C
- **Header File:** `stdarg.h` for variadic functions
- **Memory Management:** Manual memory allocation and deallocation
- **Build System:** Makefile
- **Version Control:** Git & GitHub
- **Operating Systems:** Linux (Ubuntu 22.04), macOS

---

Feel free to customize this README further to match your personal style or add any additional information you find relevant.
