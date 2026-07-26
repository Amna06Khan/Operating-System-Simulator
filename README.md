<h1 align="center">💻 Operating System Simulator</h1>

<p align="center">
  <strong>A Terminal-Based Operating System Simulator built in C, demonstrating core Operating System concepts including process scheduling, multitasking, memory management, and task control.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Operating%20Systems-Project-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Process%20Scheduling-Implemented-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

# 📖 Overview

**Operating System Simulator** is a terminal-based application developed in **C** as part of an **Operating Systems** course project.

The simulator replicates the behavior of an operating system kernel by managing multiple user-space programs, scheduling processes, allocating system resources, and handling task execution. It provides a practical implementation of fundamental operating system concepts through an interactive command-line interface.

The project demonstrates how an operating system coordinates process execution, manages CPU scheduling, switches between user and kernel modes, and controls multiple tasks simultaneously within a simulated environment.

---

# ✨ Features

### ⚙️ Process Management

- Multi-Tasking Environment
- Process Creation & Execution
- Process State Management
- Start, Block, Resume & Minimize Tasks

### 🧠 CPU Scheduling

- High Priority Queue — Round Robin (RR)
- Medium Priority Queue — First Come First Serve (FCFS)
- Low Priority Queue — Shortest Job First (SJF)
- Multi-Level Scheduling Strategy

### 💾 System Management

- Memory Management Simulation
- Core/CPU Resource Management
- User Mode & Kernel Mode Switching
- Interactive Command-Line Interface

### 📦 Built-in Applications

- Stopwatch
- Calculator
- Alarm Clock
- Guess Game
- Minesweeper
- Calendar
- To-Do List
- Notepad
- File Manager
- Number Converter
- Timer
- Random Number Generator
- Quiz Game
- Dice Roller
- Basic Shell

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| C | Programming Language |
| Operating System Concepts | Core Implementation |
| Process Scheduling Algorithms | CPU Scheduling |
| Memory Management | Resource Allocation |
| Terminal / Command Line | User Interface |

---

# 📂 Project Structure

```text
Operating-System-Simulator
│
├── main.c
├── main
│
├── tasks/
│   ├── calculator.c
│   ├── stopwatch.c
│   ├── alarm_clock.c
│   ├── guess_game.c
│   ├── minesweeper.c
│   ├── calendar.c
│   ├── todo_list.c
│   ├── notepad.c
│   ├── file_manager.c
│   ├── number_converter.c
│   ├── timer.c
│   ├── random_number_generator.c
│   ├── quiz_game.c
│   ├── dice_roller.c
│   ├── basic_shell.c
│   └── ...
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/USERNAME/Operating-System-Simulator.git
```

### Navigate to the Project

```bash
cd Operating-System-Simulator
```

### Compile the Simulator

```bash
gcc main.c -o main
```

### Compile Individual Tasks

Example:

```bash
gcc tasks/calculator.c -o tasks/calculator
```

Compile the remaining task files in the same way.

### Run the Simulator

```bash
./main
```

---

# 🎯 Learning Outcomes

This project strengthened my understanding of:

- Operating System Fundamentals
- Process Scheduling Algorithms
- Round Robin Scheduling
- First Come First Serve (FCFS)
- Shortest Job First (SJF)
- Multitasking
- Process State Management
- User & Kernel Mode Switching
- Memory Management Concepts
- Resource Allocation
- System Programming in C
- Debugging & Problem Solving

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, consider giving it a **Star ⭐** on GitHub.

---

<p align="center">
Made with ❤️ using <strong>C</strong>
</p>
