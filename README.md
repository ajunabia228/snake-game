# 🐍 Snake — Retro Edition

A classic Snake game built from scratch using vanilla HTML, CSS, and JavaScript. No frameworks, no libraries — just clean browser code with a retro arcade aesthetic.

<p align="center">
  <img src="screenshots/mainmenu.png" width="60%" alt="Main Menu Screen" />
</p>

<p align="center">
  <a href="https://ajunabia228.github.io/snake-game/">
    <img src="https://img.shields.io/badge/▶%20PLAY%20IT%20LIVE-00ff88?style=for-the-badge&logoColor=black" alt="Play it live">
  </a>
</p>

---

## Gameplay

Use the arrow keys to guide the snake. Eat the red food to grow and score points. Don't hit the walls or yourself!

<p align="center">
  <img src="screenshots/gameplay.png" width="60%" alt="Gameplay" />
</p>

<p align="center">
  <table align="center">
    <tr>
      <th>Key</th>
      <th>Action</th>
    </tr>
    <tr>
      <td align="center"><code>↑ ↓ ← →</code></td>
      <td>Move snake</td>
    </tr>
    <tr>
      <td align="center"><code>Space</code></td>
      <td>Pause / Resume</td>
    </tr>
  </table>
</p>

<p align="center">
  <img src="screenshots/gameover.png" width="60%" alt="Game over screen" />
</p>

<p align="center">😱 Make sure not to collide into the walls or else the game's over! 😱</p>

---

## Features

- 🎮 Start menu with difficulty selection (Easy / Medium / Hard)
- ⏱ Countdown timer before each game starts
- 📈 Level system — speed increases as you score higher
- 🏆 Persistent high score saved in your browser
- 🔊 Chiptune background music + sound effects (Web Audio API)
- ⏸ Pause, Replay, and Menu buttons
- 👁 Snake eyes that follow direction
- 🎨 Retro scanline aesthetic with subtle canvas grid

---

## Run locally

```bash
git clone https://github.com/ajunabia228/snake-game.git
cd snake-game
```

Then open `index.html` in your browser, or use the **Live Server** extension in VS Code.

---

## Built with

<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API">
    <img src="https://img.shields.io/badge/Web%20Audio%20API-FF4455?style=for-the-badge&logo=webaudio&logoColor=white" alt="Web Audio API" />
  </a>
</p>

---

## Credits

Base game logic adapted from [Think like a programmer: How to build Snake](https://www.freecodecamp.org/news/think-like-a-programmer-how-to-build-snake-using-only-javascript-html-and-css-7b1479c3339e/) by Panayiotis Nicolaou on freeCodeCamp. Extended with additional features and UI improvements.

Font: [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) by CodeMan38, via Google Fonts (SIL Open Font License)
