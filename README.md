# RXP Guide Generator

Free web tool to generate Rested XP guide strings for any BattleTag.

**Live:** https://inariaa.github.io/rxp_decrypter/

## How it works

- Fetches the latest encrypted guide from this repo (`guide.txt` / `guide_de.txt`)
- Re-encrypts it with your BattleTag in the browser
- You copy the result and paste it into RXPGuides in-game

## Files

| File | Purpose |
|------|---------|
| `index.html` | The web tool (GitHub Pages) |
| `guide.txt` | English guide (encrypted, fake tag) |
| `guide_de.txt` | German guide (encrypted, fake tag) |

## Updating guides

Replace `guide.txt` and/or `guide_de.txt` in this repo. The site picks up changes automatically on next visit or "Check for Updates".
