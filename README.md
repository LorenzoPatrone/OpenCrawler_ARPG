# OpenRogue

The inspiration for this project comes from Rogue, a classic fantasy game designed to run on **UNIX†** systems. <br/>
Known for its procedurally generated dungeons and challenging gameplay, *Rogue* has inspired an entire genre known as *roguelikes*. <br/>
This project is developed in Java and aims to recreate the spirit of *Rogue* while adding modern touches to it.

---

# 📋 Features

### Core Features

**Procedural Dungeon Generation** - Dungeons are generated procedurally, ensuring a unique experience in every playthrough. <br/>
**Turn-Based Gameplay** - Players and enemies take turns to move, attack, and interact with the environment. <br/>
**Permadeath** - Emulates the original Rogue challenge: when the player dies, the game restarts from the beginning. <br/>
**Inventory Management** - Players can collect, use, and manage items like potions, weapons, and armor. <br/>
**Enemies with Basic AI** - Hostile creatures patrol the dungeon, attack the player, and follow simple behavior patterns. <br/>

### Additional Features

**Fog of War** - Areas of the dungeon are hidden until the player explores them. <br/>
**Item Identification System** - Potions, scrolls, and other items need to be identified before knowing their effects. <br/>
**ASCII Art-Based Visuals** - A minimalist, retro-style interface for a true roguelike feel. <br/>
**Save and Load System** - Players can save their progress and resume the game later. <br/>
**Random Events** - Traps, secret doors, or special rooms add unpredictability to the dungeon. <br/>

### Optional/Stretch Goals

**Customizable Characters** - Players can choose from different classes or attributes. <br/>
**Boss Fights** - Epic battles against powerful dungeon bosses. <br/>
**Achievements** - Track player progress with in-game achievements. <br/>
**Modular Codebase for Future Enhancements** - Easy-to-extend architecture for adding new features like GUI or additional content. <br/>
**Tutorial or Help System** - An introductory tutorial or help menu to guide new players. <br/>

---

## 🎮 Demo

*Coming Soon*: Screenshots, gameplay videos, and a downloadable demo.
Here’s a quick preview of how the game looks and works:

---

## 🚀 Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Before we begin, make sure to have the following installed: <br/>
[**Java Development Kit**](https://www.oracle.com/java/technologies/downloads/archive/) (JDK) 17 or higher. <br/>
[**Git**](https://git-scm.com/downloads) <br/>
[**Gradle**](https://gradle.org/install/) (optional, as the project includes a Gradle wrapper) <br/>

### Clone the Repository
```bash
git clone https://github.com/your-username/OpenCrawler_ARPG.git
cd OpenCrawler_ARPG
```

### Build and Run
1. Compile the project:
    ```
        ./gradlew build
    ```
2. Run the game:
    ```
        ./gradlew run
    ```

---

## 🤝 Contributions

Thank you for your interest in this project! This is a personal learning initiative, and I am not currently accepting general contributions or feature requests.
However, if you discover a security vulnerability, I encourage you to report it responsibly. Please refer to the [SECURITY](SECURITY) Policy for detailed instructions.

---

## 🗺️ Roadmap

Below is an overview of the project's development plan.
Features marked with ✅ are complete, while others are in progress or planned for future updates.

Phase 1: Core Features
- [ ] Procedural dungeon generation
- [ ] Turn-based movement and combat
- [ ] Basic enemy AI
- [ ] ASCII-based visuals
- [ ] Inventory management

Phase 2: Enhanced Gameplay
- [ ] Fog of war (hidden areas until explored)
- [ ] Item identification system
- [ ] Save and load functionality
- [ ] Random events (traps, secret rooms, etc.)
- [ ] Permadeath system

Phase 3: Stretch Goals
- [ ] Boss fights
- [ ] Customizable characters (e.g., classes or attributes)
- [ ] Achievements system
- [ ] Modular codebase for easier feature extensions
- [ ] Graphical user interface (GUI)

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- Rogue devs – For pioneering the roguelike genre and providing the inspiration for this project.
- Open-source Roguelike community – For sharing knowledge, tools, and resources that have been invaluable for creating games in this genre.
- [NetHack](https://nethack.org/) – For being a significant influence in the development of procedural generation and roguelike mechanics.

A special thank you to anyone who has shared tutorials, articles, or open-source code related to roguelike development.

---
