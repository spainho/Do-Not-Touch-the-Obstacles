# 🎮 Do-Not-Touch-the-Obstacles

A simple browser-based endless runner game where you run, jump, duck, collect coins, avoid obstacles, complete missions, unlock achievements, and explore different worlds.

## 🚀 Features

- 🏃 Endless runner gameplay
- 🪙 Collect coins and spend them in the character shop
- ❤️ 1 life per run
- 🏆 Score and high-score system
- ⚡ Speed gradually increases during a run
- 🛡️ Shield and ⚡ speed power-ups
- 🌙 Day/night cycle
- 🌍 Five different worlds:
  - Classic
  - Desert
  - Forest
  - Snow
  - Space
- 🎭 9 character skins
- 📋 Missions with bonus coin rewards
- 🏅 Achievements
- 🌵 Multiple obstacle types:
  - Cactus
  - Rock
  - Spikes
  - Flying bird
- ⬆️ Jumping
- ⬇️ Ducking
- 📱 Mobile jump and duck controls
- 💾 Progress is saved with browser `localStorage`
- ⏸️ Pause system

## 🎮 Controls

### Computer

| Action | Control |
|---|---|
| Jump | `Space` or `Arrow Up` |
| Duck | `Arrow Down` or `S` |
| Pause | `P` |

### Mobile

Use the on-screen **JUMP** and **DUCK** buttons.

## 🌍 Worlds

The game includes five selectable worlds:

- **Classic**
- **Desert**
- **Forest**
- **Snow**
- **Space**

Your selected world is saved in the browser.

## 🎭 Character Shop

Coins can be used to unlock different character skins.

| Character | Cost |
|---|---:|
| Blue | Free |
| Red | 25 coins |
| Green | 50 coins |
| Cyan | 75 coins |
| Purple | 100 coins |
| Orange | 125 coins |
| Pink | 150 coins |
| Gold | 200 coins |
| Black | 300 coins |

Purchased characters and the selected character are saved with `localStorage`.

## 📋 Missions

Complete missions during a run to earn bonus coins.

| Mission | Reward |
|---|---:|
| Reach 100 score | 10 coins |
| Collect 5 coins | 15 coins |
| Reach 300 score | 25 coins |

## 🏅 Achievements

The game includes achievements for reaching milestones and completing challenges:

- **First Steps** — Start a run
- **Rookie Runner** — Reach a score of 100
- **Speed Star** — Reach a score of 500
- **Legendary Runner** — Reach a score of 1,000
- **Coin Collector** — Collect 10 coins in one run
- **Mission Master** — Complete all 3 missions in one run

## 🛠️ Technology

This game is built with:

- HTML
- CSS
- JavaScript
- Browser `localStorage`

The game is contained in a single `index.html` file, so it can be hosted easily with GitHub Pages.

## ▶️ Play the Game

**[Play Do-Not-Touch-the-Obstacles](https://spainho.github.io/Do-not-touch-the-obstacles/)**

## 🌐 GitHub Pages

To publish the game with GitHub Pages:

1. Put `index.html` in your repository.
2. Make sure it is in the location used by your GitHub Pages deployment.
3. Go to **Settings → Pages** in your repository.
4. Select **Deploy from a branch**.
5. Select your `main` branch and the `/ (root)` folder.
6. Save the settings.
7. Open your GitHub Pages website after deployment finishes.

## 💾 Saved Progress

The game uses the browser's `localStorage` to save:

- Coins
- High score
- Purchased characters
- Current character
- Selected world
- Unlocked achievements

Because the data is stored in the browser, progress is normally tied to the browser/device being used.

## 📁 Project Structure

```text
Do-Not-Touch-the-Obstacles/
├── index.html
└── README.md