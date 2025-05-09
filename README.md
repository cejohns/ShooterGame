# ShooterGame

ShooterGame is a first-person shooter demo built with Unreal Engine 4. It showcases core shooting mechanics, enemy AI, level design, and integrates both Blueprint and C++ elements to deliver a polished gameplay experience.

## Features

* **Player Mechanics:** Movement (W/A/S/D), Jump, Crouch, Sprint
* **Shooting System:** Multiple weapons, aiming, reloading, projectile and hitscan support
* **Enemy AI:** Basic patrol, detection, and engagement behaviors
* **Health & Damage:** Health pools for player and enemies, damage feedback, and respawn logic
* **Level Design:** Test maps with cover, obstacles, and dynamic lighting
* **User Interface:** HUD displaying health, ammo count, and crosshair
* **Modular Architecture:** Easily extendable for adding new weapons, AI states, and levels

## Requirements

* **Operating System:** Windows 10 (64-bit) or macOS
* **Engine Version:** Unreal Engine 4.26 or later
* **IDE:** Visual Studio 2017+ (Windows) or Xcode 10+ (macOS)
* **Additional Tools:** Git LFS (for large asset files)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/cejohns/ShooterGame.git
cd ShooterGame
```

### Install Dependencies

```bash
git lfs install
git lfs pull
```

## Opening the Project

1. Launch **Unreal Engine 4 Editor**.
2. Click **Open Project** and navigate to `ShooterGame/ShooterGame.uproject`.
3. Select the project file and click **Open**.

## Building from Source

### Windows

1. Double-click `ShooterGame.uproject` in Explorer to generate Visual Studio solution files.
2. Open `ShooterGame.sln` in Visual Studio.
3. Select **Development Editor** configuration and **Build**.
4. Click **Play** in the Editor or press **F5** to run.

### macOS

1. Double-click `ShooterGame.uproject` to generate Xcode project files.
2. Open the generated `.xcodeproj` in Xcode.
3. Build the project and launch the Editor.

## Controls

| Action        | Key / Button        |
| ------------- | ------------------- |
| Move          | W / A / S / D       |
| Jump          | Space               |
| Crouch        | Left Ctrl           |
| Sprint        | Left Shift          |
| Aim           | Right Mouse Button  |
| Shoot         | Left Mouse Button   |
| Reload        | R                   |
| Switch Weapon | Mouse Wheel / 1 / 2 |

## Roadmap

* [ ] Additional weapon types (e.g., grenades, lasers)
* [ ] Multiplayer support via Unreal Networking
* [ ] Advanced AI behaviors and tactics
* [ ] Expanded level environments and themed maps
* [ ] Polish UI, audio, and visual effects

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/MyFeature`.
3. Commit your changes: `git commit -m "Add MyFeature"`.
4. Push to your branch: `git push origin feature/MyFeature`.
5. Open a Pull Request.

## License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

## Contact

Cory Johnson – [GitHub Profile](https://github.com/cejohns)
