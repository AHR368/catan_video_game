# 🌍 Catan — Local Browser Game

This is a **browser-based implementation of the board game Catan** with a fixed physical map layout (fixed road placement & edge ports). It runs entirely in your browser as a **single `catan.html` file** — no backend required.

![Screenshot](screenshot.png) <!-- Optional: add a screenshot -->

---

## ✨ Features

- 🎲 **Pass & play** mode (local multiplayer)
- 🎨 Setup modal for **custom player names & colors**
- 🏗️ Build roads, settlements, and cities directly on the map
- 🃏 Development card buying & playing
- 🏴‍☠️ Robber mechanics with discard rules
- 🏦 Trading system (bank 4:1, 3:1 harbors, 2:1 specialty harbors)
- 📜 Built-in **game log**
- 📊 Player panels with resources, VP, and current turn
- 🚀 No install needed — just open the HTML file in a browser

---

## 📂 Project Structure

```

.
├── catan.html     # Main game file (HTML + CSS + JS inlined)
├── favicon.ico    # Optional favicon
├── wood.webp      # Resource tile images
├── brick.webp
├── sheep.webp
├── wheat.webp
├── ore.webp
├── desert.webp
└── README.md

````

> ⚠️ The HTML references resource images like `wood.webp`, `brick.webp`, etc.  
> To have proper tile graphics, place those images in the same folder as `catan.html`.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/catan.git
   cd catan
```

2. Open the game:

   * Just double-click **`catan.html`** to open in your browser

---

## 🎮 How to Play

* Click **"New Game (setup)"** to choose number of players, names, and colors.
* Place starting settlements and roads during setup (snake draft order).
* Each turn:

  * Roll dice
  * Collect resources from adjacent hexes
  * Build / trade / play development cards
  * End turn
* First player to **10 Victory Points (VP)** wins.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3** (custom styles + Google Fonts)
* **Vanilla JavaScript**
* **SVG rendering** for board & pieces

No external frameworks required.


---

## 🙌 Acknowledgments

Inspired by the classic board game *Catan*.
This project is an educational/fan-made implementation for local use only.

