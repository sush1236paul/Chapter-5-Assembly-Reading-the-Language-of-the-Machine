# Chapter-5-Assembly-Reading-the-Language-of-the-Machine# Chapter 5 - Assembly: Reading the Language of the Machine

This repository contains my practice programs and notes for Chapter 5 of Offensive Security Programming Fundamentals.

## Objectives

- Understand what assembly language is
- Learn how C code is translated into assembly
- Read basic assembly instructions
- Understand stack frames and function calls
- Learn calling conventions
- Recognize if statements and loops in assembly
- Debug programs using GDB

---

## Topics Covered

### 5.1 What is Assembly?
- Introduction to assembly language
- Using `objdump`
- Understanding the compilation process

**File:**
- `5.1_what_is_assembly/hello.c`

---

### 5.2 First Disassembly
- Disassembling a simple program
- Reading generated assembly code

**File:**
- `5.2_first_disassembly/add.c`

---

### 5.3 Essential Instructions
- `mov`
- `add`
- `sub`
- `cmp`
- `jmp`
- `call`
- `ret`

**File:**
- `5.3_essential_instructions/math.c`

---

### 5.4 Stack Frame Explained
- Stack memory
- Function stack frames
- `push`
- `pop`
- `rbp`
- `rsp`

**File:**
- `5.4_stack_frame/function_demo.c`

---

### 5.5 Calling Conventions
- Function arguments
- Register-based argument passing
- `rdi`
- `rsi`
- `rdx`

**File:**
- `5.5_calling_conventions/add.c`

---

### 5.6 Reading an if Statement in Assembly
- Conditional logic
- `cmp`
- `je`
- `jne`
- `jg`
- `jge`
- `jl`
- `jle`

**Files:**
- `5.6_if_statement/if_demo.c`
- `5.6_if_statement/password_check.c`

---

### 5.7 Reading a Loop in Assembly
- Loop recognition
- Counter variables
- Conditional jumps
- Repeated execution flow

**Files:**
- `5.7_loops/count_loop.c`
- `5.7_loops/while_loop.c`

---

### 5.8 Debugging with GDB
- Breakpoints
- Stepping through code
- Viewing variables
- Viewing assembly instructions

**File:**
- `5.8_gdb_debugging/debug_demo.c`

---

## Tools Used

- GCC
- objdump
- GDB
- Linux Terminal

---

## Skills Learned

- Basic assembly analysis
- Reading compiler output
- Understanding program execution flow
- Function call analysis
- Stack frame analysis
- Assembly debugging
- Reverse engineering fundamentals

---

## Repository Structure

```text
chapter-05-assembly/
│
├── 5.1_what_is_assembly/
├── 5.2_first_disassembly/
├── 5.3_essential_instructions/
├── 5.4_stack_frame/
├── 5.5_calling_conventions/
├── 5.6_if_statement/
├── 5.7_loops/
└── 5.8_gdb_debugging/
