# Attack Game 🎮🗡️

A lightweight **“lifebar scramble”** game running in a single HTML file, using the Vue 3 Option API.
The goal is simple: Reset the computer to zero with *Attack*, *Heavy Attack* or *Heal*!

<img width="1916" height="539" alt="Image" src="https://github.com/user-attachments/assets/8f8555d5-318b-4215-ac3e-8ef144acb685" />

---

## Features
- ⚔️ **Normal Attack** — 7‑15 random damage
- 💥 **Healing Attack** — Can be used once every 4th turn, 15‑30 damage
- 🩹 **Healing** — Restores 15‑20 health (max 100)
- 🔄 **New Game** button
- 🎨 Simple percentage bar animation (CSS scope)

---

## Setup

```bash
git clone https://github.com/Enver-Onur-Cogalan/Vue-OptionAPI--Attack-Game.git
cd attack-game-vue
# No dependencies — just open index.html in the browser!
```

> If you are using VS Code or Xcode, open the file directly; the “Live Server” plugin or Safari will be sufficient.

---

## Technologies Used

| Technology | Description |
|-----------|----------|
| **Vue 3** | Via CDN, Option API |
| **CSS** | Simple stylesheet, box-shadow & transition |
| **HTML** | Single page (without SPA) |

---

## Project Structure

```
attack-game-vue/
│
├─ index.html # Vue CDN + game template
├─ script.js # Game mechanics & Vue instance
└─ style.css # Simple style file
```

---

## Lisans

MIT — use it as you wish, I would appreciate it if you gave me stars! ⭐

<p align="center">Made with ❤️ and <img alt="Vue" src="https://vuejs.org/images/logo.png" width="24"></p>
