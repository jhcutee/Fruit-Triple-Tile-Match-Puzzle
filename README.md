# Tiletopia - Tile Match Puzzle 🧩

A fun and engaging tile-matching puzzle game built with Unity. Match three or more tiles to clear them from the board and progress through challenging levels!

## 🎮 Game Features

- **Classic Tile Matching**: Match 3 or more identical tiles to clear them
- **Multiple Levels**: Progressive difficulty with various challenges  
- **Sound Effects**: Immersive audio experience with background music and SFX
- **Mobile Optimized**: Designed for mobile devices with touch controls
- **Ad Integration**: Google Mobile Ads implementation

## 📱 Demo

[![Game Demo](Assets/Demo/TripleTileItplus.mp4)](Assets/Demo/TripleTileItplus.mp4)

*Click to view the gameplay demo video*

## 🛠️ Technical Details

### Built With
- **Unity 2021.3+** (recommended)
- **C#** - Primary programming language
- **DOTween** - Animation library
- **LeanTween** - Lightweight tweening library
- **Google Mobile Ads** - Advertisement integration

### Project Structure
```
Assets/
├── Scenes/           # Game scenes (Home, GamePlay, Loading)
├── Script/           # C# scripts and game logic
├── Sprite/           # Game sprites and textures
├── Prefab/           # Unity prefabs
├── AudioClip/        # Sound effects and background music
├── Demo/             # Demo video
└── Resources/        # Runtime loaded assets
```

## 🚀 Getting Started

### Prerequisites
- Unity Hub
- Unity Editor 2021.3 or later
- Visual Studio or preferred C# IDE

### Installation
1. Clone or download this repository
2. Open Unity Hub
3. Click "Add" and select the project folder
4. Open the project in Unity
5. Load the `Home` scene to start

### Building the Game
1. Go to **File → Build Settings**
2. Select your target platform (Android/iOS recommended)
3. Click **Build** or **Build and Run**

## 🎯 How to Play

1. **Objective**: Clear tiles by matching 3 or more identical tiles
2. **Controls**: Tap/click on tiles to select them
3. **Scoring**: Earn points for each successful match
4. **Progression**: Complete levels to unlock new challenges

## 📂 Key Scripts

- `GameController.cs` - Main game logic and flow
- `TileManager.cs` - Tile behavior and management
- `LevelController.cs` - Level progression and data
- `UIManager.cs` - User interface management
- `AdsManager.cs` - Advertisement integration

## 🔧 Configuration

### Audio Settings
Audio mixer settings can be adjusted in `Assets/AudioClip/NewAudioMixer.mixer`

### Level Data
Level configurations are managed through `LevelData.cs` and can be customized for different difficulty curves.

## 📄 License

This project is licensed under the terms specified in the LICENSE file.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you encounter any issues or have questions, please create an issue in this repository.

---

**Enjoy playing Tiletopia! 🎉**
