# 🎆 DGA Cyber 2026 Countdown

A futuristic New Year's Eve celebration experience built with a single HTML file, HTML5 Canvas, vanilla JavaScript, and the Web Audio API.

The app counts down to **January 1, 2026**, then transforms into an interactive cyberpunk fireworks display with synthesized sound, neon effects, and a typewriter-style greeting.

## ✨ Features

- **New Year countdown:** Displays the remaining days, hours, minutes, and seconds until 2026.
- **Celebration transition:** Automatically switches from the countdown to the New Year celebration when the target time is reached.
- **Canvas fireworks:** Renders launch trails, explosions, particles, gravity, friction, fading, and color effects.
- **Interactive fireworks:** Click or tap anywhere on the screen to launch a firework toward that position.
- **Cyberpunk visual design:** Includes glitch typography, neon colors, glowing text, animated backgrounds, and a terminal-inspired interface.
- **Typewriter greeting:** Reveals the celebration message progressively after the countdown.
- **Synthesized sound effects:** Creates launch, explosion, countdown, and interaction sounds with the Web Audio API.
- **Audio controls:** Adjust volume, mute or unmute sound, and persist the selected volume locally.
- **Pause and resume:** Pause the animation and countdown, then continue when ready.
- **Responsive canvas:** Resizes to fit desktop, tablet, and mobile screens.
- **Keyboard shortcuts:** Provides keyboard controls for fireworks, audio, volume, and playback.
- **Accessibility support:** Includes a keyboard-accessible skip link and interactive control labels.

## 🛠️ Built with

- **HTML5** for the page structure and interface controls
- **HTML5 Canvas** for real-time fireworks rendering
- **CSS3** for the cyberpunk theme, glitch effects, responsive layout, and animations
- **JavaScript (ES6+)** for countdown logic, particle physics, interaction handling, and application state
- **Web Audio API** for generated sound effects
- **Web Storage API** for remembering the volume setting

## 🚀 Getting started

### Prerequisites

You only need a modern browser with support for HTML5 Canvas and the Web Audio API. No build tools, dependencies, or backend server are required.

### Run locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/david-godspower/dga-cyber-2026-countdown.git
   ```

2. **Open the project directory**

   ```bash
   cd dga-cyber-2026-countdown
   ```

3. **Launch the experience**

   Open `index.html` in a modern browser, or serve the project with a local development server such as VS Code Live Server.

The repository also contains `firework.html`, an additional standalone celebration page with the same interactive fireworks experience.

## 🎮 Controls

| Action | Function |
|---|---|
| Click or tap | Launch a firework at the selected location |
| Spacebar | Pause or resume the countdown and animation |
| `F` | Launch a firework at a random location |
| `M` | Mute or unmute sound |
| Arrow Up | Increase the volume |
| Arrow Down | Decrease the volume |
| Escape | Resume the experience if it is paused |
| Volume slider | Set the sound volume directly |
| Mute button | Toggle audio output |
| Pause/Resume button | Toggle animation and countdown playback |

## 🔊 Audio behavior

Most browsers block audio until the user interacts with the page. Click, tap, or use a control once to enable synthesized sound.

The selected volume is stored locally under the `newYearVolume` key. Muting affects generated sound but does not stop the visual fireworks.

## 📁 Project structure

```text
dga-cyber-2026-countdown/
├── index.html      # Main countdown and celebration experience
├── firework.html   # Standalone fireworks celebration page
├── LICENSE         # MIT license
└── README.md       # Project documentation
```

## 🌐 Browser support

Use a current version of Chrome, Edge, Firefox, or Safari for the best experience. The project relies on:

- HTML5 Canvas
- Web Audio API
- `localStorage`
- Pointer and keyboard events

If audio is unavailable or blocked, the visual countdown and fireworks can still be used.

## 👤 Author

**David Godspower Ajala**

- [GitHub](https://github.com/david-godspower)
- [Portfolio](https://david-godspowerajala.me)
- [LinkedIn](https://www.linkedin.com/in/david-godspower-ajala/)
- [Facebook](https://facebook.com/DavidGodspowerAjalaDGA/)
- [Twitter/X](https://x.com/DavidGAjala)
- [Email](mailto:ajaladavid11@gmail.com)

## 📄 License

This project is available under the [MIT License](LICENSE).

---

**Happy New Year 2026!** 🎉
