# ICS3202-Assembly-Austin-Wangahu-146361-
# Assembly Programming Tasks

## Overview

This project consists of four assembly programs designed to demonstrate core concepts such as control flow, array manipulation, subroutines, and port-based control simulation. Each program is implemented in a pseudo x86 assembly format with emphasis on branching, looping, stack management, and I/O control.

---

### **1. Control Flow and Conditional Logic**
**Purpose:**  
This program prompts the user for a number and classifies it as "POSITIVE," "NEGATIVE," or "ZERO" using both conditional and unconditional jumps.

**Challenges:**  
Efficiently managing control flow while keeping the program concise required balancing conditional and unconditional jumps for clarity and optimal performance.

---

### **2. Array Manipulation with Looping and Reversal**
**Purpose:**  
The program accepts an array of integers and reverses it in place without using additional memory.

**Challenges:**  
Reversing the array in place involved precise pointer manipulation to avoid using extra memory. The biggest challenge was ensuring pointers do not overlap or corrupt data.

---

### **3. Modular Program with Subroutines for Factorial Calculation**
**Purpose:**  
This program computes the factorial of a given number using a recursive subroutine, preserving register values via the stack to ensure modularity.

**Challenges:**  
Managing the stack during recursion to preserve intermediate results and registers was critical. Mismanagement could easily lead to stack overflow or corrupted results.

---

### **4. Data Monitoring and Control Using Port-Based Simulation**
**Purpose:**  
Simulates a control program that reads a "sensor" value and controls a "motor" or triggers an "alarm" based on predefined thresholds.

**Challenges:**  
Simulating real-time port behavior in memory required handling specific memory addresses as ports, with bit manipulation to reflect motor and alarm status.

---

## Compilation and Execution Instructions

### **Prerequisites:**
- **Assembler and Linker:** Ensure you have an assembler like `NASM` and a linker like `ld` installed.
- **Linux Environment:** The code assumes a Linux environment for system calls.
