# Skull-Clicker 💀

A tiny, single-file web clicker — a lightweight, playful HTML experiment for fast prototyping and micro-interactions.

---

## What it is
Skull-Clicker is a compact clicker-style web game implemented as a single HTML file (includes CSS and JavaScript in-file). It's designed for quick interaction, low friction, and easy customization — perfect for experimenting with small game mechanics, animations, and sound.

---

## Features
- Single-file delivery: index.html contains markup, styles, and scripts
- Click/tap-driven gameplay for desktop and mobile
- Simple scoring and visual feedback (animations, counters)
- Tiny footprint — instant load, no build step required
- Easy to fork and adapt for other microgames or UI experiments

---

## How to run
No build tools required — just open the file in your browser.

- Open locally:
  - Serve locally to avoid browser restrictions (recommended):
    ```bash
    # Python 3
    python -m http.server 8000
    # then open http://localhost:8000/index.html
    ```
- For web version, just open (https://hugochan117.github.io/Skull-Clicker/%F0%9F%92%80Clicker%E2%84%A2.html)

---

## How to play (quick)
- Click or tap the skull (or main game element) to earn points/skulls.
- Watch for animations and feedback on each click.
- (If the repo includes upgrades/levels) Click to earn currency, then purchase upgrades from the UI.

If you want exact controls or mechanics written here, tell me whether the game has upgrades, idle mechanics, or power-ups and I’ll detail them.

---

## Customize
- Change visuals: edit CSS variables or the embedded stylesheet.
- Tweak mechanics: open the script inside `index.html` and update values for score increments, delays, or thresholds.
- Add assets: drop images, audio files, and update asset paths in the HTML.

If you'd like, I can add inline comments in `index.html` to show where to modify common values.

---

## Development notes
- Language: 100% in a single HTML file (markup, style, and behaviour included).
- No external dependencies — intentionally minimal for portability.

---

## Contributing
Small contributions welcome:
- Open an issue for bugs, suggestions, or feature requests.
- Fork the repo, make changes, and open a pull request.
- Keep changes small and focused (single concern per PR).

Please include a screenshot/GIF and short description when submitting UI/UX changes.

---

## Credits
- Built and maintained by HugoChan117
- Inspired by classic clicker mechanics and microgame design patterns
