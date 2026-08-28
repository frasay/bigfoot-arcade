# 🦶 BIGFOOT — 90s Arcade Forest Runner

> INSERT COIN — PRESS ANY KEY

A retro 90s arcade-style side-scrolling runner starring Bigfoot. Jump rolling logs,
double-jump to catch UFO forcefield orbs, and chase the hi-score. Built as a single,
zero-dependency HTML file with code-driven pixel art, WebAudio chip SFX, and full
CRT treatment (scanlines, phosphor flicker, vignette) at an authentic 480×270.

## ▶️ Play

**Live:** https://frasay.github.io/bigfoot-arcade/

Works on desktop and mobile (touch).

## 🕹️ Controls

| Input | Action |
|---|---|
| `SPACE` / `↑` / `ENTER` / tap | Jump |
| Jump again mid-air | Double-height jump (up to UFO altitude) |
| `M` | Mute / unmute |

## 🏆 Scoring

| Event | Points |
|---|---|
| Clear an obstacle | +100 |
| Catch a UFO forcefield orb | +250 |
| Smash a log while shielded | +50 |
| Surviving | +10/sec |

Hi-score is saved locally in your browser (`localStorage`).

## 👾 How it plays

- **Rolling logs** visibly rotate and speed up the longer you survive — doubles appear later
- **Stumps and rocks** mix up the jump timing
- When you hear the **UFO hum**, get ready: the orb drops from the tractor beam at
  double-jump height. Catch it for a **10-second forcefield** — plow through logs for bonus points
- **3 lives**, hit flicker, and a proper GAME OVER continue countdown, arcade-cabinet style

## 🎵 Music

The game streams `music.mp3` (a 160bpm chiptune chase theme, "Bigfoot Run") from the
repo root. If the file is missing the game runs silently — chip SFX still work.

## 🛠️ Tech

- Single `index.html` — no frameworks, no build step, no dependencies
- Canvas 2D at 480×270 with chunky pixel scaling
- WebAudio-synthesised sound effects (jump chirps, pickup arpeggio, crash noise, UFO hum)
- Code-driven pixel art: parallax dusk forest, run/jump sprite animation, particles

## 📜 Credits

Game design, code, pixel art and music produced with AI assistance for Guy Fraser.

---

*CONTINUE? 9…8…7…*
