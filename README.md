# Conflict Tracker — US · Israel · Iran

A clean, installable PWA for tracking the US-Israel-Iran conflict in real time. Pulls neutral briefings from Reuters, BBC, NPR, PBS, and AP on demand.

## Features

- **Live briefings** — AI-powered news fetch using web search, summarized neutrally
- **4 categories** — Diplomatic, Humanitarian, Military, International
- **Scrolling ticker** — Live headline feed across the top
- **Installable PWA** — Pin to taskbar on Windows/Mac, home screen on mobile
- **Dark interface** — Easy on the eyes for regular check-ins
- **Source links** — Every card links back to the original article

## Trusted Sources Only

Reuters · BBC · NPR · PBS · Associated Press

No partisan or sensationalist outlets.

## Setup

### Option 1 — GitHub Pages (recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your tracker will be live at `https://yourusername.github.io/conflict-tracker`

### Option 2 — Run locally

Just open `index.html` in any modern browser. No build step, no dependencies.

> **Note:** The AI briefing feature requires an active internet connection and calls the Anthropic API. Make sure you're connected when hitting "Fetch briefing."

## Install as a Taskbar App

Once the page is open in Chrome or Edge:

1. Look for the install icon in the address bar (or click the three-dot menu)
2. Select **"Install Conflict Tracker"** or **"Add to taskbar"**
3. The app opens in its own window and appears in your taskbar/dock

On mobile (iOS/Android): use **Share → Add to Home Screen**.

## Project Structure

```
conflict-tracker/
├── index.html       # Main app (self-contained)
├── manifest.json    # PWA manifest
├── sw.js            # Service worker (offline support)
├── icon-192.png     # App icon
├── icon-512.png     # App icon (large)
└── README.md
```

## Roadmap

- [ ] Auto-refresh on a timer (every 4 hours)
- [ ] Pinned timeline view of key events
- [ ] Key players glossary panel
- [ ] Export briefing as PDF
- [ ] Email digest option

## License

MIT — personal use, modify freely.
