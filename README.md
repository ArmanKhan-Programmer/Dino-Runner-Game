# 🦖 Dino Runner

A simple, lightweight **Dino Runner game** built using **HTML5 Canvas, CSS, and Vanilla JavaScript**.

The game is inspired by the classic browser dinosaur runner experience. Jump over incoming cacti, survive as long as possible, and beat your high score!

## 🎮 Demo

You can play the game by opening `index.html` directly in any modern web browser.

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

The game also supports touch interaction through the canvas.

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **HTML5 Canvas API**
* **Web Audio API**
* **LocalStorage API**

No external dependencies are required.

## 📂 Project Structure

```text
dino-runner/
│
├── index.html
└── README.md
```

The complete game is contained inside `index.html`, including the HTML structure, styling, and JavaScript game logic.

## ⚙️ How It Works

### Game Loop

The game uses `requestAnimationFrame()` to continuously update and render the game.

```javascript
requestAnimationFrame(t => this.loop(t));
```

The game updates:

* Dinosaur movement
* Gravity and jumping
* Cactus movement
* Score
* Game speed
* Collision detection
* Visual rendering

## 🦖 Dinosaur

The dinosaur has gravity-based jumping physics. When the player jumps, an upward velocity is applied, followed by gravity that brings the dinosaur back to the ground.

## 🌵 Obstacles

Cactus obstacles are generated with different sizes and shapes.

The obstacle spacing is randomized, while the game speed gradually increases to make the game more challenging.

## 💯 Scoring System

The score continuously increases while the player survives.

A high score is stored in the browser using:

```javascript
localStorage
```

This allows the high score to remain available even after refreshing the page.

## 🔊 Sound Effects

The game uses the **Web Audio API** to generate simple sound effects for:

* Jumping
* Reaching score milestones
* Crashing

Audio is initialized after user interaction to comply with browser audio restrictions.

## 🌙 Dark Mode

The game automatically detects the user's system color preference using:

```javascript
prefers-color-scheme
```

It adapts the page and game canvas for both light and dark themes.

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/dino-runner.git
```

### 2. Open the project

```bash
cd dino-runner
```

### 3. Run the game

Simply open:

```text
index.html
```

in your browser.

No installation or build process is required.

## 🌐 Deploy on GitHub Pages

You can easily deploy this project using **GitHub Pages**.

1. Push the project to a GitHub repository.
2. Open the repository's **Settings**.
3. Go to **Pages**.
4. Select the main branch.
5. Select the root folder.
6. Save the settings.
7. GitHub will provide a live website URL.

## 📸 Game Preview

Add a screenshot of your game here:

```markdown
![Dino Runner Screenshot](screenshot.png)
```

## 🔮 Future Improvements

Some ideas for future versions:

* [ ] Add pause/resume functionality
* [ ] Add different dinosaur skins
* [ ] Add more obstacle types
* [ ] Add power-ups
* [ ] Add difficulty levels
* [ ] Add background music
* [ ] Add mobile-specific UI controls
* [ ] Add a leaderboard
* [ ] Add start and settings screens
* [ ] Add animated background elements

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve the project:

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
