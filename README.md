# 🎮 Rock Paper Scissors (Python CLI Game)

A fully interactive command-line **Rock, Paper, Scissors** game built with Python using object-oriented programming (OOP). This project demonstrates clean code structure, class inheritance, and multiple AI strategies with different difficulty levels.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Game Modes](#-game-modes)
- [How to Play](#-how-to-play)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Code Highlights](#-code-highlights)
- [Example Gameplay](#-example-gameplay)
- [What I Learned](#-what-i-learned)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📖 Overview

This project is a terminal-based game where the player competes against computer-controlled opponents. Each opponent uses a different strategy, making the game progressively more challenging.

The core idea of the project is to model each player as a class and use inheritance to define different behaviors. This approach makes the code scalable and easy to extend.

---

## 🚀 Features

- 🎯 Play against multiple AI difficulty levels  
- 🔁 Dynamic gameplay with different strategies  
- 📊 Score tracking system  
- 🧠 AI learning behavior using `learn()` method  
- 🧩 Modular and extensible OOP design  
- ⚠️ Input validation for better user experience  

---

## 🧠 Game Modes

| Level | Name        | Behavior |
|------|------------|----------|
| 1    | Super Easy | Always plays **rock** |
| 2    | Easy       | Cycles through moves (*rock → paper → scissors*) |
| 3    | Medium     | Reflects your previous move |
| 4    | Hard       | Plays randomly |

---

## 🕹️ How to Play

1. Run the game:
   ```bash
   python game.py
