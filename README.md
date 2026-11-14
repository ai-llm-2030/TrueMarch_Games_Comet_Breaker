# Comet Breaker

**Four glass worlds, 32 stages, bosses that shoot back. Catch the capsules, dodge the grey one.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Comet Breaker — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Comet_Breaker/"><b>▶ Play Comet Breaker in your browser</b></a>
</p>

## What's new: the Wall Builder

Design your own wall and hand it to a friend. **Title → Wall Builder** opens the real 14 × 12 brick grid with every brick in the game (colours, cracked and thick glass, silver plate, gold, powder kegs, sliders, star bricks). Paint it, pick the world it lives in, then **Test it** with your paddle: the same three stars as the campaign (clear · no paddle lost · beat the par it works out for you), and your best score on that wall is kept.

**Copy code** puts a short share code on the clipboard (`CB0:..1K-..2E**2E-…`, with a check letter so a typo is refused); **Load code** opens a friend's wall, ready to play or remix.

| Keys in the builder | |
|---|---|
| Arrows / WASD + Space | Move the cursor, paint (the same brick again erases) |
| 0–6, Q / E | Eraser, colours 1–6, cycle through every brick |
| Mouse / touch | Click or drag to paint · right-click erases · tap the palette and buttons |
| T · C · L | Test it · copy code · load code |
| F · B · N · X | Mirror on/off · world · surprise wall to remix · clear |

<p align="center">
  <img src="assets/screenshot-builder.png" alt="Comet Breaker — the Wall Builder" width="820">
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Comet Breaker — gameplay" width="820">
</p>

## More screenshots

<table>
<tr><td width="50%"><img src="assets/screenshot-map.png" alt="The world map"><br><sub>The world map</sub></td><td width="50%"><img src="assets/screenshot-play-b.png" alt="Mid-stage"><br><sub>Mid-stage</sub></td></tr>
<tr><td width="50%"><img src="assets/screenshot-result.png" alt="Out of paddles: the result"><br><sub>Out of paddles: the result</sub></td><td width="50%"><img src="assets/screenshot-how.png" alt="Every capsule and brick"><br><sub>Every capsule and brick</sub></td></tr>
</table>

## Controls

| Keys | Action |
|---|---|
| ← → / A D or mouse | Move the paddle |
| Space | Launch & fire |
| Esc | Menu |
| P | Pause |
| M | Sound on / off |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Comet_Breaker.git
cd TrueMarch_Games_Comet_Breaker
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Comet_Breaker/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── lib/
│   ├── arcade.js     shared helpers: crisp canvas, frame loop, input, theme
│   └── arcade.css    shared look
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Comet Breaker** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
