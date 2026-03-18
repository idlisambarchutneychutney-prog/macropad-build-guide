# 🛠️ Macropad Build Guide

An interactive step-by-step guide for building a custom RP2040 macropad from scratch.
6 keys, 2 rotary encoders, per-key RGB, hand-designed PCB, QMK firmware, 3D printed case.

**→ Live demo:** [[your-username.github.io/macropad-build-guide](#)](https://github.com/idlisambarchutneychutney-prog/macropad-build-guide/blob/main/index.html)

---

## What it does

- Drag a slider to set your timeline — anywhere from a 3-day sprint to a 30-day relaxed build
- The entire schedule recalculates live — day numbers, phase labels, PCB order warnings, all of it
- 75 task checkboxes that save your progress in the browser (localStorage)
- 4 colour themes: Dark, Light, Hacker Green, Warm Amber — also saved across refreshes
- Full QMK firmware code reference, shopping list with buy links, and a resource hub
- Zero dependencies. No npm, no build step. Just open index.html and it works.

---

## Usage

1. Clone or download the repo
2. Open `index.html` in any browser
3. That's it

To host it online, enable GitHub Pages in your repo settings:
Settings → Pages → Deploy from branch → main → / (root)
Your guide goes live at `username.github.io/repo-name` in about 2 minutes.

---

## What you're building

| Part | Spec |
|---|---|
| Microcontroller | Raspberry Pi Pico (RP2040) |
| Keys | 6× MX switches |
| Encoders | 2× EC11 rotary encoders |
| RGB | SK6812 MINI-E per-key LEDs |
| PCB | Custom KiCad design, fab'd at JLCPCB |
| Firmware | QMK |
| Case | 3D printed PLA/PETG |
| Budget | ~$40–60 USD |

---

## Contributing

PRs and issues are welcome. If you find a broken link, wrong pin number,
or want to add a section — open an issue first so we can discuss it before
you spend time writing code.

Please keep the no-dependencies rule. This project's whole point is that
anyone can open one HTML file and use it. No bundlers, no frameworks.

---

## License

MIT — do whatever you want with it. See `LICENSE` for the full text.
