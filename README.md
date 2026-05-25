# 🌙 Sleep Timer

A clean, minimal sleep countdown timer built for sharing via Discord.  
Dark amoled aesthetic with animated nebula background, smooth progress bar, and shareable links.

---

## Features

- **Countdown timer** with HH:MM:SS display
- **Preset durations** — 30m, 1h, 2h, 3h, 6h, 8h
- **Custom time input** — set any hours, minutes, seconds
- **Smooth progress bar** — turns red in last 10%, green when done
- **Animated nebula background** — live canvas with drifting color blobs and twinkling stars
- **Discord Share button** — copies a link with your duration encoded (`?t=seconds`) so anyone who opens it gets the timer pre-set
- **Discord rich embed** — shows title and accent color when pasted in Discord
- Fully self-contained single HTML file — no dependencies, no server required

---

## Usage

1. Open the site
2. Pick a preset duration or type a custom time
3. Hit **Start**
4. Click **Discord Share** to copy a shareable link
5. Paste the link in Discord — anyone who clicks it gets the same timer

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript
- Canvas API for the animated background
- Google Fonts — Syne + DM Mono
- No frameworks, no npm, no build step

---

## Deployment

Hosted on **Vercel** via GitHub.  
Any push to `main` auto-deploys.

---

## License

See [LICENSE](./LICENSE) — All Rights Reserved.  
© 2026 mrkraps (github.com/bliper2)
