# 🎮 Conway's Game of Life

A beautiful, interactive implementation of Conway's Game of Life built with vanilla HTML, CSS, and JavaScript.

## 🌟 About

Conway's Game of Life is a cellular automaton devised by mathematician John Conway in 1970. It's a zero-player game where the evolution is determined by its initial state, requiring no further input. The game demonstrates how complex patterns can emerge from simple rules.

## 🎯 Rules

The universe is a two-dimensional grid of cells, each of which can be either alive or dead. The state of each cell evolves based on four simple rules:

1. **Underpopulation**: Any live cell with fewer than 2 live neighbors dies
2. **Survival**: Any live cell with 2 or 3 live neighbors survives
3. **Overpopulation**: Any live cell with more than 3 live neighbors dies
4. **Reproduction**: Any dead cell with exactly 3 live neighbors becomes alive

## 🚀 Getting Started

### Prerequisites

No dependencies required! Just a **modern web browser**.

### Installation

0. You can simply visit the game [here](https://tarikcolic.github.io/gameoflife/index.html) in your browser, or clone the repo for yourself.

1. Clone the repository
```bash
git clone https://github.com/tarikcolic/gameoflife.git
```

2. Navigate to the directory
```bash
cd gameoflife
```

3. Open `index.html` in your browser
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply drag and drop the `index.html` file into your browser.

## 🎮 Usage

1. **Visit the website**: [gameoflife/index.html](https://tarikcolic.github.io/gameoflife/index.html)
2. **Start simulation**: The game begins when the site loads
5. **Reset**: Click the "Rereun Simulation" button to reset the entire grid


## 🎨 Classic Patterns to Try

Try creating these famous patterns:

- **Glider**: A pattern that moves diagonally across the grid
- **Blinker**: The simplest oscillator that alternates between two states
- **Toad**: A period-2 oscillator
- **Beacon**: Another period-2 oscillator
- **Pulsar**: A period-3 oscillator
- **Glider Gun**: Creates an endless stream of gliders

## 🛠️ Technologies Used

![HTML5](http://img.shields.io/badge/-HTML5-eee?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](http://img.shields.io/badge/-CSS3-eee?style=flat-square&logo=css3&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/-JavaScript-eee?style=flat-square&logo=javascript&logoColor=DD9C25)

## 📂 Project Structure

```
gameoflife/
├── index.html          # Main HTML structure
├── styles.css          # Styling and animations
├── game.js             # Game logic and simulation
└── README.md           # Documentation
```

## 🎓 Learning Resources

- [Wikipedia: Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
- [LifeWiki](https://conwaylife.com/wiki/Main_Page) - Comprehensive pattern database
- [The Nature of Code](https://natureofcode.com/book/chapter-7-cellular-automata/) - Chapter on Cellular Automata

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Share interesting patterns you've discovered

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📫 Contact

Reac out to me on [LinkedIn](https://www.linkedin.com/in/tarikcolic/) ~

---

⭐ Star this repo if you enjoyed playing with it!

## 🎉 Fun Fact

Despite its simplicity, Conway's Game of Life is Turing complete, meaning it can simulate any computer algorithm given enough time and space!
