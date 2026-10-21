# Tidy Rounds

A daily cleaning checklist, room by room, with a timer so cleaning doesn't eat the whole day.

## What it does

- Rooms with daily tasks you check off; checks clear each morning
- Set a cap (10, 15, 20 or 30 minutes), hit Start, and do what you can
- Anything you didn't get to shows up in **Up first** at the top the next day, longest-waiting first
- Days you don't clean don't pile up — Up first just waits for you
- Add or remove rooms and tasks; everything saves on the device

## Files

```
index.html             # The whole app (no build step)
manifest.webmanifest   # Lets phones install it with an app icon
sw.js                  # Service worker so it opens offline
icons/                 # App icons (192, 512, Apple touch icon)
```

## Running it

Hosted free on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

- **iPhone:** open the Pages link in Safari → Share → Add to Home Screen
- **Android:** open it in Chrome → ⋮ menu → Add to Home screen / Install app

When you change a file, bump `VERSION` in `sw.js` so phones pick up the update.

Built by Anna via Claude.
