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






Tic-Tac-Toe Game (8086 Assembly Language)
📌 Project Description

This project is a 2-player Tic-Tac-Toe game developed using 8086 Assembly Language (DOS interrupts). The game allows two players (Player X and Player Y) to play turn by turn on a 3x3 grid. The system checks for winning conditions and displays the result accordingly.

Additionally, the game maintains a score record and saves it into a file named scores.txt.

⚙️ Features
2-player gameplay (Player X vs Player Y)
Turn-based input system
Dynamic board update after each move
Win detection logic for all combinations:
Rows
Columns
Diagonals
Score tracking:
Wins
Losses

File handling:
Saves scores in scores.txt

🖥️ How It Works
The game displays a Tic-Tac-Toe board with positions (1–9).
Players take turns entering a position number.
The program:
Updates the board
Stores moves in arrays (playerX and playerY)
After each move:
It checks if the current player has won.
If a player wins:
A winning message is displayed
Scores are updated
Data is written to scores.txt
The program exits after displaying the result.
📂 File Handling
File Name: scores.txt
Stores:
Player X Wins and Losses
Player Y Wins and Losses

Example output:
Player X : Wins = 1 Losses = 0
Player Y : Wins = 0 Losses = 1

🧠 Data Structures Used
playerX[9] → Tracks moves of Player X
playerY[9] → Tracks moves of Player Y
Board positions stored as strings (pos1 to pos9)

🛠️ Interrupts Used
INT 21H for:
Input (AH = 01H)
Output (AH = 02H, 09H)
File handling (3CH, 40H, 3EH)

▶️ How to Run
Assemble the code using an assembler like:
MASM or TASM
Link the program
Run in DOSBox or any 8086 emulator

⚠️ Limitations
No validation for already occupied positions
No draw/tie detection
File overwrites every time (no append mode)
Limited UI (text-based only)

🚀 Possible Improvements
Add input validation (prevent overwriting moves)
Implement draw detection
Improve UI formatting
Add single-player mode (AI)
Store cumulative scores instead of overwriting file

👨‍💻 Author
Developed as part of Assembly Language learning/project work

📎 Conclusion
This project demonstrates:

Low-level programming concepts
Memory handling
Conditional logic
File operations in Assembly

It is a solid example of building a complete interactive program using 8086 Assembly Language.

⭐ Support
If you like these project, give it a ⭐ on GitHub and share it!
