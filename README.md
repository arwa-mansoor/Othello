# ♟️ Othello

> **A classic strategy game, rebuilt. Sharpen your wits. Outsmart the AI — or challenge a friend in 2-Player mode!**

---

![C++](https://img.shields.io/badge/Language-C++-blue.svg)  
![raylib](https://img.shields.io/badge/Graphics-raylib-lightblue.svg)  
![Minimax](https://img.shields.io/badge/AI-Minimax%20with%20Alpha--Beta-brightgreen.svg)  
![Mode](https://img.shields.io/badge/Modes-Single%20%26%20Two%20Player-purple.svg)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🕹️ About the Game

**Othello Reimagined** is a modern C++ take on the timeless Othello/Reversi board game, featuring a clean GUI, smooth animations, and two exciting game modes:

- **Single Player vs AI** (powered by Minimax with Alpha-Beta pruning)
- **Two Player Mode** (play locally with a friend)

Built with:

- **raylib** for responsive graphics  
- **C++ OOP** structure for maintainability and scalability  
- **Minimax AI** for competitive single-player gameplay  
- **File I/O** for persistent score history  

---

## 🎮 How to Play

- Two players (Human vs AI or Human vs Human) take turns placing discs.
- A valid move must outflank at least one of the opponent’s discs.
- Flanked discs are flipped to your color.
- When neither player can move, the game ends — the player with the **most discs wins**.

---

## 🧠 AI Features

- **Minimax with Alpha-Beta Pruning** ensures strong and efficient decision-making.
- Uses a **weighted evaluation matrix** to prioritize moves strategically.
- Adjustable search depth for balancing difficulty.

---

## 👯 Game Modes

- 🧠 **Single Player vs AI**  
- 👥 **Two Player (Local PvP)** – take turns on the same device

---

## 📸 Screenshots

### 🎯 Main Menu (Mode Selection)

<img width="638" height="661" alt="image" src="https://github.com/user-attachments/assets/b0366981-8c19-4dff-973e-6c08f7698e67" />

---

### 📋 Game Instructions

<img width="637" height="662" alt="image" src="https://github.com/user-attachments/assets/1bb08b22-ffe2-4408-9cb0-87f090b65190" />

---

### 🧩 Gameplay Interface (Two Player Mode)

<img width="637" height="661" alt="image" src="https://github.com/user-attachments/assets/f5a2ffb0-3df7-42d8-9734-6c2d44d08e0a" />

---

### 📊 Game Over Screen

<img width="633" height="662" alt="image" src="https://github.com/user-attachments/assets/79bd2b7a-5b66-4a5d-a4d3-13565c918e13" />

---

### 📊 Score History

<img width="641" height="663" alt="image" src="https://github.com/user-attachments/assets/359289f3-a75a-4fae-86a5-d283bd04f1e2" />

---

## 🚀 How to Run

1. Make sure you have **raylib installed** on your system.
2. Compile the game using:

   ```bash
   g++ main.cpp -o othello -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
3. Run the executable:
   
   ```bash
   ./othello

---

## 🛠️ Features

- Full 8x8 Othello board with smooth visuals  
- Single Player with smart AI opponent  
- Local Two Player mode  
- Highlighted legal moves  
- Real-time score display  
- Game Over screen with result  
- File-based score saving  
- Animated piece flipping  
- Clean, minimal interface  

---

## 💡 Tips & Strategy

- Prioritize **corner control** — they can't be flipped!  
- Don’t rush to take many pieces early.  
- Use **edges** to reduce AI’s mobility.  
- Think 2–3 moves ahead, especially near the endgame.

---

## 🔮 Future Enhancements

- Add undo/replay functionality  
- Timer and leaderboard  
- Sound effects and background music  
- Multiplayer over network  
- Randomized AI styles  

---

## 👨‍💻 Author

**Arwa Mansoor**  
*Student at FAST NUCES | Game Developer | Othello Enthusiast*
