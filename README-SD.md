# 🌵 Spiky Dasher

A challenging 2D platformer game for Android where you dash, jump, and wall-slide through spike-filled levels to collect all the coins!

---

## 🎮 Features

### Core Gameplay
- **Wall Jumping** - Slide down walls and kick off to reach new heights
- **Double Jumping** - Extra air control with a second jump
- **Precision Platforming** - Navigate through tight gaps and spike-filled corridors
- **Collectibles** - Gather all coins to complete each level

### 5 Unique Levels

| Level | Name | Difficulty | Description |
|-------|------|------------|-------------|
| 1 | Spike Valley | 🟢 Easy | Learn the mechanics with forgiving platforms |
| 2 | Wall Jump Way | 🟢 Medium | Master wall jumping with extensive wall spikes |
| 3 | Sky High | 🟡 Medium-Hard | Smaller platforms and dangerous ceilings |
| 4 | Gauntlet Run | 🟠 Hard | Dense spike patterns and narrow paths |
| 5 | Spike Storm | 🔴 Expert | Maximum hazards - only for the skilled! |

### Game Features
- ⏱️ **Timer** - Race against the clock
- 🏆 **Per-Level Best Times** - Track your fastest run on each level
- 💀 **Death Counter** - See how many times you fell
- 🎯 **Level Selection** - Choose your challenge with color-coded difficulty
- 📱 **Touch Controls** - Responsive on-screen controls

---

## 🕹️ Controls

| Button | Action |
|--------|--------|
| ◄ | Move Left |
| ► | Move Right |
| ▲ | Jump / Double Jump / Wall Jump |

**Tips:**
- Hold against a wall while falling to wall slide
- Press jump while wall sliding to wall jump
- You have 2 jumps in the air (double jump)

---

## 📱 Screenshots

*Coming soon*

---

## 🛠️ Technical Details

- **Platform:** Android
- **Language:** Kotlin
- **Graphics:** Custom SurfaceView rendering
- **Min SDK:** Android 10.0 (API 26)

### Project Structure

```
app/src/main/java/com/matthew_world/spikydasher/
├── MainActivity.kt      # Entry point
├── GameView.kt          # Main game renderer & logic
├── GameThread.kt        # Game loop thread
├── Player.kt            # Player physics & rendering
├── Platform.kt          # Platform objects
├── Obstacle.kt          # Spike obstacles
├── Collectible.kt       # Coin collectibles
├── LevelBuilder.kt      # Level design & generation
├── LevelManager.kt      # Level state management
├── LevelData.kt         # Level data structures
└── LevelValidator.kt    # Coin placement validation
```

---

## 🚀 Building

### Prerequisites
- Android Studio Arctic Fox or later
- JDK 11+
- Android SDK 34

### Build Steps

```bash
# Clone the repository
git clone https://github.com/MatthewDelong/Spiky-Dasher.git
cd Spiky-Dasher

# Build debug APK
./gradlew assembleDebug

# Install on connected device
./gradlew installDebug
```

---

## 🎯 How to Play

1. **Tap to Start** - From the main menu, tap anywhere to open level select
2. **Choose a Level** - Select from 5 levels with increasing difficulty
3. **Collect All Coins** - Navigate through platforms and avoid spikes
4. **Beat Your Time** - Complete the level as fast as possible!
5. **Try Again** - After completing, choose another level or retry for a better time

---

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

---

## 👨‍💻 Author

**Matthew World**

---

*Dash carefully! 🌵*
