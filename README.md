# 🚀 INFINITE BOUNCE

An endless, neon-styled vertical arcade game that runs directly in your browser. Bounce upward, dodge hazards, grab power-ups, and beat your personal best. Built with plain HTML5 Canvas, with no frameworks, no assets, and no installation.

### ▶️ [Play Now: a4x-coder.github.io/Infinite-Bounce](https://a4x-coder.github.io/Infinite-Bounce/)

---

## ✨ Features

- **Endless gameplay.** There are no levels, stages, or bosses. Height is your only progression.
- **Procedural platforms.** Every run is different, and generation always leaves a reachable path.
- **Six platform types:** normal, moving, breakable, disappearing, spring, and danger.
- **Five power-ups:** Jet Boost, Shield, Magnet, Slow Motion, and Double Score.
- **Gradual difficulty.** The opening is gentle, then gaps widen, platforms narrow and speed up, and hazards become more frequent.
- **Polished game feel.** Delta-time physics, squash-and-stretch, particle trails, platform fragments, screen shake, a smooth camera, and a parallax background that shifts colour as you climb.
- **Synthesised audio.** Sound effects and ambient music are generated with the Web Audio API, with separate Sound and Music toggles.
- **Saved progress.** Your best score and audio preferences persist through `localStorage`.
- **Works offline.** Once the page has loaded, no internet connection is needed.

## 🎮 Controls

| Platform | Action | Input |
|---|---|---|
| 📱 Mobile | Move left / right | Touch and drag anywhere on the screen |
| 💻 Desktop | Move left / right | `←` `→` or `A` `D` (click and drag also works) |
| 💻 Desktop | Pause / resume | `Space` |
| 💻 Desktop | Restart after game over | `R` |

Bouncing is automatic, and leaving one side of the screen brings you back in from the other.

## 🧱 Platform Types

| Platform | Behaviour |
|---|---|
| Normal | Stable, can be bounced on repeatedly |
| Moving | Slides horizontally, getting faster with height |
| Breakable | Gives one bounce, then shatters |
| Disappearing | Fades out shortly after contact |
| Spring | Launches you much higher |
| Danger | Spiked, so avoid it (a Shield absorbs one hit) |

## ⚡ Power-Ups

| Power-up | Effect |
|---|---|
| **J** Jet Boost | Rapid upward launch while invulnerable |
| **S** Shield | Absorbs one hazard collision |
| **M** Magnet | Pulls nearby orbs toward you |
| **T** Slow Motion | Slows moving platforms and hazards |
| **2x** Double Score | Doubles the points you earn for a limited time |

## 🛠️ Tech Stack

- HTML5 Canvas 2D with procedural graphics
- Vanilla JavaScript, with a single `requestAnimationFrame` loop and delta-time updates
- Web Audio API for all sound
- `localStorage` for saved data
- One self-contained `index.html` file

## 🚀 Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/A4X-Coder/Infinite-Bounce.git
   ```
2. Open `index.html` in any modern browser.

No build step, server, or dependencies are required.

## 🌐 Deploy with GitHub Pages

1. Push `index.html` to the repository's main branch.
2. Go to **Settings → Pages**.
3. Under **Source**, select the main branch and the root folder, then save.
4. Your game will be live at `https://<username>.github.io/Infinite-Bounce/`.

## 📱 Compatibility

Designed for modern Android browsers (including Chrome) and modern desktop browsers. The layout is portrait-first and adapts to different screen sizes.

## 👤 Author

**A4X-Coder**
GitHub: [github.com/A4X-Coder](https://github.com/A4X-Coder)
Repository: [github.com/A4X-Coder/Infinite-Bounce](https://github.com/A4X-Coder/Infinite-Bounce)

---

## 📄 License

No license is specified in this repository unless a LICENSE file is added. Until then, reuse and redistribution permissions should not be assumed.
