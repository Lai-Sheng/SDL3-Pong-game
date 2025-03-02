# SDL3 C++ Pong Game

## 🎮 Introduction
This is a fully implemented and optimized **SDL3 C++ Pong game**, focusing on a unique **defensive gameplay mechanic**. Unlike traditional Pong, where players score by attacking, this version challenges the player to **defend the ball and survive as long as possible**.

## ✨ Features
### 🔹 Core Gameplay Mechanics
- ✅ **Defensive Pong System** – Players control a paddle to **block the ball**, rather than aiming for a goal.  
- ✅ **Single-Player Mode** – A solo challenge focusing on reflex speed and survival time.  
- ✅ **Dynamic Scoring System** – Score increases over time, rewarding endurance.  
- ✅ **Winning Condition** – The game ends with a victory screen when the player reaches the maximum score.

### 🔹 UI & Game Flow
- ✅ **Start Menu** – Players can select difficulty levels, which affect ball speed and power-up frequency.  
- ✅ **In-Game UI Display:**
  - **Current Score**
  - **Target Score (Winning Limit)**
  - **Game Status (Ongoing / Ended)**
- ✅ **Game Over Screen** – Displays appropriate results when the player wins or loses.

### 🔹 Physics & Collision Handling
- ✅ **Optimized Collision Detection** – Ensures accurate ball collisions with paddles and walls, preventing glitches.  
- ✅ **Realistic Ball Rebound Mechanics** – The ball bounces based on entry angles and speed for a natural experience.  
- ✅ **Dynamic Ball Speed** – Ball velocity gradually increases over time to enhance the challenge.  
- ✅ **Speed Limit Control** – Prevents excessive speed that could negatively impact gameplay.

### 🔹 Power-Ups & Enhancements
- ✅ **Various Power-Ups with Unique Effects:**
  - 🎯 **Paddle Size Modifier** – Increases or decreases paddle size.
  - ⚽ **Ball Size Modifier** – Alters the ball's dimensions.
  - 🚀 **Speed Boost** – Increases or decreases ball speed.
  - 🛡️ **Invincibility Mode** – Temporary shield preventing score loss.
- ✅ **Efficient Power-Up Management** – Implemented using `unordered_map`, `vector`, and `enum` for easy expansion and clarity.  
- ✅ **Software Timer Implementation** – Ensures balanced timing for power-up generation.

### 🔹 Code Structure & Optimization
- ✅ **Modularized Codebase** – The main program (`main.cpp`) is split into multiple `.cpp` and `.h` files for better readability and maintainability.  
- ✅ **Enhanced Object-Oriented Programming (OOP) Design:**
  - Utilizes **classes, inheritance, and encapsulation** to organize game objects (e.g., `Paddle`, `Ball`, `PowerUp`).
  - Uses **efficient data structures** to manage game logic, reducing redundant code.
- ✅ **Performance Optimization** – Improved collision detection and object update mechanisms to minimize unnecessary computations.

## 🚀 Future Updates
🔜 Planned improvements to enhance the gameplay experience:
- 🆚 **Multiplayer Mode** – Introduce local two-player battles.
- 🎵 **Background Music & Sound Effects** – Enhance immersion.
- 🎨 **Expanded Game Scenes & Animations** – Add more variety to visual elements.

## 🔧 Requirements
- **C++ Compiler (GCC/Clang/MSVC)**
- **SDL3 Library**
- **CMake (Optional for build automation)**

## 🛠️ Installation & Compilation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/sdl3-pong-game.git
cd sdl3-pong-game
```

### **2️⃣ Install Dependencies**
Ensure SDL3 is installed on your system:
```bash
# Ubuntu/Linux
sudo apt install libsdl3-dev

# macOS (Using Homebrew)
brew install sdl3

# Windows (Use vcpkg or download from SDL's official site)
vcpkg install sdl3
```

### **3️⃣ Build and Run**
#### Using CMake:
```bash
mkdir build && cd build
cmake ..
make
./pong_game
```

#### Using a Simple Compiler Command:
```bash
g++ -o pong_game main.cpp Game.cpp Paddle.cpp Ball.cpp -lSDL3 -std=c++17
./pong_game
```

## 📜 License
This project is released under the **MIT License**. See `LICENSE` for details.

## 🤝 Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for suggestions and improvements.

## 📬 Contact
For any questions or feedback, reach out via GitHub Issues or email at **your.email@example.com**.

---
🕹️ **Enjoy the Game & Have Fun!** 🎉

