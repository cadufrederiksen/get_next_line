# 📜 Get Next Line - Reading Lines from Files

![Get Next Line](https://img.shields.io/badge/Language-C-blue) ![Makefile](https://img.shields.io/badge/Tool-Makefile-yellow) ![Norminette](https://img.shields.io/badge/Style-Norminette-green)

The **Get Next Line** project aims to implement a C function that efficiently reads one line from a file descriptor. This project helps students explore memory manipulation, file management, and the use of static variables, addressing common practical issues in operating systems.

---

## 📋 Project Objective

🔹 Create a function capable of reading **one line at a time** from a file or standard input.  
🔹 Manage multiple file descriptors simultaneously.  
🔹 **Optimize dynamic memory allocation** for efficient reading.  
🔹 Understand the use of **static variables** to store information between function calls.

---

## 📚 Main Concepts

- 🧠 **Memory Manipulation**: efficient use of dynamic memory allocation to store data.  
- 📂 **File Handling**: reading data through file descriptors.  
- 📌 **Static Variables**: persisting data between consecutive function calls.  
- 🔄 **Buffer Management**: reading in blocks to improve function performance.  
- 🔗 **Multiple Descriptors**: support for different files being read simultaneously.

---

## ✨ Implemented Features

### 🔤 Line Reading
- Reads **one complete line** at a time, including the newline character (`\n`).  
- Returns the read content as a dynamically allocated string.  

### 🛠️ Advanced Support
- **Multiple file descriptors**: the function manages several files or inputs simultaneously.  
- **Efficient memory handling**: prevents memory leaks by freeing allocated buffers after use.  
- **Error management**: handles situations such as invalid descriptors or unexpected end-of-file.

### 🔄 Architecture and Optimization
- **Configurable buffers**: buffer size adjustable using the `BUFFER_SIZE` macro.  
- **Persistence with static variables**: stores remaining data between successive function calls.

---

## 🛠️ Tools and Standards

| Tool/Standard         | Description                                                        |
|-----------------------|--------------------------------------------------------------------|
| **GIT**               | Version control to organize and track code progress.               |
| **Makefile**          | Automates compilation and file generation.                         |
| **Norminette**        | Checks compliance with 42 coding style standards.                  |

---
