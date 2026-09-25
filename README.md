# 🦖 Dino Runner

A simple, lightweight **Dino Runner game** built using **HTML5 Canvas, CSS, and Vanilla JavaScript**.

The game is inspired by the classic browser dinosaur runner experience. Jump over incoming cacti, survive as long as possible, and beat your high score!

## 🎮 Live Demo

🚀 **Play the game online:**
https://armankhan-programmer.github.io/Dino-Runner-Game/

👉 **[Play Dino Runner](https://armankhan-programmer.github.io/Dino-Runner-Game/)**

## ✨ Features

* 🦖 Pixel-style dinosaur character
* 🌵 Multiple cactus obstacle variations
* 🎮 Keyboard controls
* 📱 Touch and mouse support
* 💯 Live score system
* 🏆 Persistent high score using `localStorage`
* 📈 Increasing game speed and difficulty
* 🔊 Jump, point, and crash sound effects
* 🌙 Automatic light/dark mode support
* 📐 Responsive canvas
* ⚡ No external libraries or frameworks

## 🕹️ Controls

| Action  | Control       |
| ------- | ------------- |
| Jump    | `Space`       |
| Jump    | `↑ Arrow`     |
| Jump    | Mouse click   |
| Jump    | Touch         |
| Restart | `Space` / Tap |

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **HTML5 Canvas API**
* **Web Audio API**
* **LocalStorage API**

## 📂 Project Structure

```text
Dino-Runner-Game/
│
├── index.html
└── README.md
```

## ⚙️ How It Works

The game uses `requestAnimationFrame()` to continuously update and render the game.

The game handles:

* Dinosaur movement
* Jumping and gravity
* Cactus movement
* Score calculation
* Increasing game speed
* Collision detection
* High-score storage
* Game rendering

## 💯 Scoring System

The score increases while the player survives. The highest score is stored in the browser using `localStorage`, allowing it to persist between sessions.

## 🔊 Sound Effects

The game uses the **Web Audio API** to generate sound effects for:

* Jumping
* Score milestones
* Crashing

## 🌙 Dark Mode

The game automatically detects the system's light/dark color preference and adjusts the game interface accordingly.

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/armankhan-programmer/Dino-Runner-Game.git
```

Enter the project directory:

```bash
cd Dino-Runner-Game
```

Then open `index.html` in your browser.

No installation or build process is required.

## 🌐 Deployment

The project is deployed using **GitHub Pages**.

### Live Website

**https://armankhan-programmer.github.io/Dino-Runner-Game/**

## 🔮 Future Improvements

* [ ] Add pause/resume functionality
* [ ] Add different dinosaur skins
* [ ] Add more obstacle types
* [ ] Add power-ups
* [ ] Add difficulty levels
* [ ] Add background music
* [ ] Add leaderboard
* [ ] Add animated background elements

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Open a Pull Request.

## 📄 License

This project is open for learning and personal use.

---

### ⭐ If you like this project

Consider giving the repository a **star ⭐** on GitHub!
