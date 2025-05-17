# Operating-System-Simulator
This project is a **terminal-based Operating System Simulator** written in **C**, built for educational purposes to demonstrate key OS concepts including **multitasking**, **process scheduling**, **memory management**, and **task control**. It simulates the functioning of an OS kernel managing various user-space programs.

## 🚀 Features

- **Multitasking environment** with process management
- **Multi-level Process Scheduling:**
  - High Priority: Round Robin
  - Mid Priority: First Come First Serve (FCFS)
  - Low Priority: Shortest Job First (SJF)
- **User/Kernel Mode switching**
- **Memory and Core management**
- Interactive **menu-driven interface**
- Task operations: Start, Minimize, Block, Resume
- Includes 15+ simulated tasks (as separate executables)

## 🧠 Included Tasks

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

Each task runs as a separate process and demonstrates user-mode program execution under simulated OS control.

## 🛠️ Technologies

- Language: **C**
- OS Concepts: Multilevel Scheduling, Process Queues, System Calls Simulation
- Environment: Terminal/Command-line based (No GUI)

## 📂 Project Structure

```bash
project/
├── main.c                  # Main OS simulator code
├── main                   # Compiled executable
└── tasks/                 # Directory containing all tasks
    ├── calculator.c
    ├── stopwatch.c
    ├── guess_game.c
    └── ...
⚙️ How to Run
Compile the project:
gcc main.c -o main
Compile individual tasks (example):
gcc tasks/calculator.c -o tasks/calculator
Do the same for other .c files in the tasks/ directory.

Run the OS Simulator:
./main

📈 Learning Outcomes
This project demonstrates:
Practical understanding of OS-level multitasking
Scheduling algorithms implementation
Memory/core resource management
Inter-process control simulation
Shell-like interaction in a terminal environment

🎓 Semester Project – MilkyWay OS Simulator
📍 FAST-NUCES | Spring 2025
## 👩‍💻 Developers
👩‍💻 Team Members: Amna Noor (23F-0811), Rao Waleed (23F-0628)
