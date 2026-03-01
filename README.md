# 🎮 Trap Adventure (Android)

A brutally challenging 2D trap-based platformer built for Android.

Trap Adventure is a fast-paced precision platformer where every step could trigger a hidden trap. Navigate through spikes, collapsing platforms, and unexpected obstacles designed to test reflexes, patience, and timing.

⚠️ This game is intentionally difficult.

---

# 📱 Features

## 🎮 Gameplay
- Classic 2D side-scrolling platformer
- Hidden and dynamic traps
- Precision-based jump mechanics
- Increasing difficulty levels
- Instant restart system
- Smooth animations

## 💣 Trap Types
- Hidden spikes
- Falling platforms
- Fake floors
- Moving blades
- Timed traps
- Trigger-based surprise traps

## ⚙️ Technical Features
- Custom game loop
- Collision detection system
- Physics-based movement
- Object-oriented architecture
- Optimized rendering using SurfaceView
- Efficient memory handling

---

# 🛠️ Tech Stack

- Java / Kotlin
- Android SDK
- Android Studio
- Canvas / SurfaceView
- XML layouts
- Gradle build system

---

# 🏗️ Architecture Overview

The project follows a modular object-oriented structure:

- **MainActivity** → Entry point
- **GameView** → Core rendering and game loop
- **GameThread** → Update & draw cycle handler
- **Player** → Player logic and movement
- **Trap** → Trap behavior system
- **LevelManager** → Level progression manager
- **CollisionDetector** → Handles collision detection

### Game Loop Structure

```java
while (isRunning) {
    update();
    draw();
}
```

---

# 🚀 Getting Started

## Requirements

- Android Studio
- Android SDK (API 21+)
- Android device or emulator

## Run the Project

1. Clone the repository
   ```bash
   git clone <repository-url>
   ```

2. Open the project in Android Studio

3. Allow Gradle to sync

4. Click **Run ▶** to install and launch the app

---

# 🎮 Controls

| Action | Control |
|--------|----------|
| Move Left | Left button |
| Move Right | Right button |
| Jump | Jump button |
| Restart | Automatic on death |

---

# 🧠 Game Mechanics

## Movement System
- Gravity-based physics
- Controlled jump velocity
- Smooth horizontal movement

## Collision System
- Rectangle-based hitboxes
- Axis-Aligned Bounding Box (AABB)
- Continuous collision checks

## Difficulty Design
- Trial-and-error gameplay
- Pattern recognition
- Hidden trap discovery

---

# 🚀 Performance Optimization

- Uses SurfaceView for efficient rendering
- Reduced object creation inside game loop
- Bitmap caching
- Optimized collision checks
- Stable frame rate performance

---

# 🔮 Future Improvements

- Additional levels
- Sound settings
- Pause system
- Save progress system
- Animated traps
- Leaderboard integration

---

# 📜 License

This project is released under the MIT License.

---

# ⭐ Support

If you like this project, consider giving it a star.
