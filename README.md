# 🚗 Road Fighter Game

A classic **2D car racing game** developed in **C++ using OpenGL (Dev C++)**. The game is inspired by the traditional Road Fighter concept with a unique fuel mechanic — the car refuels by hitting special fuel cars to survive and reach the finish line.

---

## 📌 Project Overview

This project is a desktop-based racing game where the player controls a car, avoids traffic, collects fuel from special vehicles, and tries to reach the finish line without running out of fuel.

The game demonstrates core concepts of:

* Computer Graphics using OpenGL
* Real-time game loop
* Keyboard input handling
* Collision detection
* Basic game physics

---

## 🎮 Key Features

* 🚘 Player-controlled racing car
* ⛽ Unique fuel system (refuel by hitting special cars)
* 🛣️ Endless moving road environment
* 🚧 Enemy traffic vehicles
* 🎯 Score and fuel management
* ⌨️ Smooth keyboard controls
* 🖥️ Built using Dev C++ and OpenGL

---

## 🧠 Game Concept

Unlike traditional racing games, the player's car **does not automatically refill fuel**.

* Fuel decreases continuously while driving
* Special fuel cars appear on the road
* Hitting these special cars **refills fuel**
* Player must manage fuel wisely to reach the finish line

👉 The main objective is:

> **Survive, manage fuel, avoid crashes, and reach the finish line.**

---

## 🛠️ Tech Stack

* **Language:** C++
* **Graphics:** OpenGL
* **IDE:** Dev C++
* **Platform:** Desktop

---

## 📂 Project Structure

```
Road-Fighter-Game/
│
├── road_fighter.cpp   # Main game source code
├── README.md
└── LICENSE
```

---

## ⚙️ Requirements

Make sure you have the following installed:

* Dev C++ or any C++ compiler
* OpenGL libraries
* GLUT / FreeGLUT
* Windows/Linux desktop environment

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/21BCS3014/Road-Fighter-Game.git
cd Road-Fighter-Game
```

### 2️⃣ Compile and Run

**Windows (Dev C++ / MinGW):**

```bash
g++ road_fighter.cpp -lopengl32 -lglu32 -lfreeglut -o roadfighter.exe
roadfighter.exe
```

**Linux:**

```bash
g++ road_fighter.cpp -lGL -lGLU -lglut -o roadfighter
./roadfighter
```

---

## 🎯 Controls

| Key   | Action              |
| ----- | ------------------- |
| ↑ | Accelerate / Car races  |
| ← / → | Move car left/right |
| ESC   | Exit game           |


---

## 📸 Gameplay Screenshot

> 📌 **Add your game screenshot in the repo and update the path below**

```
![Gameplay](screenshots/gameplay.png)
```

**How to add screenshot:**

1. Run the game
2. Take a screenshot
3. Create folder: `screenshots/`
4. Save image as: `gameplay.png`
5. Push to GitHub

---

## 🔮 Future Enhancements

* 🔊 Sound effects and background music
* 🏎️ Multiple difficulty levels
* 🎨 Improved graphics and textures
* 🧠 Smarter traffic AI
* 📱 Mobile/Android version

---

## 👩‍💻 Author

**Simran**
B.Tech CSE | Fresher Developer
ss6773568@gmail.com
---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you like this project, consider giving it a star on GitHub!
