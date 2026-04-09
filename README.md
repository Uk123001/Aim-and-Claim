# 🎯 Aim and Claim – Hack Assembly Game (Nand2Tetris)

**Aim and Claim** is a classic-style 2D shooting game written in the Hack Assembly language as part of the [Nand2Tetris](https://www.nand2tetris.org/) project. Built to demonstrate low-level system understanding and creative logic design, this game challenges players to shoot objects and solve math puzzles — all within the constraints of the Hack computer.

## 🕹 Game Overview

You play as the shooter in a timed arcade-style challenge. The objective is simple: **aim**, **shoot**, and **claim points**!

### 🎯 Level Structure

#### Level 1: Static Targets
- Shoot as many static objects as possible within **60 seconds**.
- Each hit gives you points.

#### Level 2 Trigger: Math Challenge
- After 60 seconds, you must answer a **math question**.
  - ✅ Correct Answer → +100 points  
  - ❌ Incorrect Answer → -1 life

#### Level 2: Moving Targets
- Survive and shoot **dynamic/moving objects**.
- Precision and timing are everything.

#### Game End:
- The game concludes with an **ending message**.
- The Hack computer gracefully **exits the game**.

---

## 🛠 Built With

- 🧠 **Hack Assembly Language**  
- 💻 [Nand2Tetris](https://www.nand2tetris.org/) Emulator Tools
- 📄 `.vm` files representing CPU-level logic for gameplay

---

## 📂 Project Structure

- Game.jack
- Gun.jack
- Main.jack
- Random.jack
- ScoreBoard.jack
- Wall.jack

---

## 🧠 How to Play

1. Download Nand2Tetris project from its official site.
2. Extract the `.zip` file
3. In the folder go to nand2tetris -> tools
4. Open `VMEmulator.bat` or `VMEmulator.sh`
5. Download the game files from this repository into a floder with it's directory known.
6. At the top left extreme click the loadProgram icon
7. Locate this game folder
8. Click the folder and open
9. Under Animate select **No animation**
10. Click the `>>` arrow on the top to start the game
11. Enjoy the game :)

---

## ⚠️ Limitations

- Designed and tested on the Nand2Tetris CPU Emulator.
- Complex animations are not possible due to lack of multi threadreading
- The screen is strictly black and white making better graphics harder

---

## 🙌 Acknowledgements

- Inspired by [Nand2Tetris](https://www.nand2tetris.org/), an open course on building a modern computer from first principles.
- Developed as part of a college project of the Elements of Computing Systems - nand2tetris course.
- This was possible only by the team effort put by my team members
  - Jiya Sachdeva
  - Harshith Laxman B
  - Ankur De

---

---

> “Simple hardware. Smart code. Big fun.”

