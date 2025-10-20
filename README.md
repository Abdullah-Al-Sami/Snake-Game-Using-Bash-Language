# 🐍 Snake Game Using Bash

### **Project Type:** Terminal Game  
### **Language:** Bash (Shell Script)  
### **Tool:** Linux Terminal / Git Bash / macOS Terminal  
### **Domain:** Game Development with Scripting  

---

## 📘 Project Description

The **Snake Game Using Bash** is a classic retro-style terminal game written entirely in Bash scripting.  
It runs directly in the terminal using **`tput`** for cursor control and **real-time key input** for movement.  
Players control a snake that grows longer by eating apples (`*`) while avoiding collisions with the walls or itself.

This project demonstrates the **power of Bash** for interactive scripting, dynamic screen rendering, and game logic without using any external dependencies.

---

## 🎯 Objectives

- Develop an interactive terminal-based Snake Game using only Bash.  
- Implement real-time input handling for movement (W, A, S, D keys).  
- Simulate game mechanics — snake growth, scoring, and collision detection.  
- Use **ANSI escape sequences** and **tput** for terminal UI control.  
- Strengthen knowledge of loops, arrays, and process signals in Bash.

---

## ⚙️ Requirements

| Tool | Description |
|------|--------------|
| **Bash Shell** | Version 4.0+ (Linux / macOS / WSL / Git Bash) |
| **tput Utility** | For terminal control |
| **sleep, awk, sed, stty** | Default Linux tools, used for logic and formatting |

---

## 🧩 Setup & Run Instructions

1️⃣ ***Clone the Repository***
```bash
git clone https://github.com/YourUsername/Snake-Game-Bash.git
cd Snake-Game-Bash
2️⃣ Give Execution Permission
bash
Copy code
chmod +x snake.sh
3️⃣ Run the Game
bash
Copy code
./snake.sh
