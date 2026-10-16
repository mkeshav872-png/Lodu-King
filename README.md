# 🎲 Ludo King

A polished, classic Ludo game that runs entirely in your browser. No installation, no dependencies, no sign-up. Just open the link and play.

### ▶ [**Play now**](https://mkeshav872-png.github.io/lodu-king/)

`https://mkeshav872-png.github.io/lodu-king/`

![Ludo King preview](og-image.png)

## Features

- **2, 3 or 4 players**, against the computer or **Pass & Play** on one device
- **4 computer levels**: Easy, Medium, Hard and Pro
- **Classic** (all 4 tokens home) and **Quick** (first token home wins) modes
- Smooth token animations, dice roll, capture effects and sound
- **Emoji reactions and quick chat** (including some Hinglish phrases)
- **6 themes** and **3 token styles**
- Your choices (theme, level, players, mode, sound) are remembered on your device
- Installable on a phone: use *Add to Home Screen*
- Works on mobile and desktop, portrait and landscape

## How to play

1. Roll a **6** to bring a token out of the yard.
2. Move clockwise around the board, then up your own coloured lane to the centre.
3. Landing on an opponent's token on a normal square sends it back to its yard.
4. Star squares and start squares are safe: no captures there.
5. A 6, a capture, or a token reaching home gives you a **bonus roll**.
6. Three 6s in a row and your turn is lost.
7. You need the exact number to reach home.

## Run locally

It is a single static page.

```bash
git clone https://github.com/mkeshav872-png/lodu-king.git
cd lodu-king
# open index.html in any browser, or serve it:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Tech

Plain HTML, CSS and vanilla JavaScript in one file (`index.html`). Sound is generated with the Web Audio API, so there are no audio files. Deployed with GitHub Pages.

## Roadmap

- [ ] Online multiplayer with room codes (play with a friend on a different phone)
- [ ] Save and resume a game in progress
- [ ] Hindi interface option

## License

MIT. See [LICENSE](LICENSE).

Made by **Keshav Mishra**
