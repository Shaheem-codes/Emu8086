# Emu8086

🐍 Snake Game in Assembly (8086)

This project is a classic Snake Game implemented in 8086 Assembly Language using BIOS and DOS interrupts. It runs in a text-mode environment and demonstrates low-level programming concepts like memory handling, keyboard input, and screen manipulation.

🚀 Features
Real-time snake movement using arrow keys
Food generation at random positions
Snake growth when food is eaten
Collision detection (self-collision = game over)
Screen wrapping (snake appears from opposite side)
Smooth rendering using BIOS interrupts

🧠 Concepts Used
8086 Assembly Programming
Interrupts
INT 10h → Video services
INT 21h → DOS services
INT 16h → Keyboard input
INT 1Ah → Timer (for randomness)

Data Structures
Arrays for snake body tracking

Game Logic
Movement handling
Direction tracking
Collision detection

🎮 Controls
Key	Action
↑ (Up)	Move Up
↓ (Down)	Move Down
← (Left)	Move Left
→ (Right)	Move Right
🛠️ How to Run
Requirements:
DOSBox or any 8086 emulator
MASM / TASM assembler

⚠️ Limitations
Runs only in text mode
No sound effects
Basic random food generation
Limited screen resolution (80x25)

⭐ Support
If you like this project, give it a ⭐ on GitHub and share it!
