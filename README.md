# DAYQUEST v1

An offline-capable, mobile-first retro RPG daily planner. No account or backend needed.

## Try locally
Serve the folder with `python -m http.server 8000`, then open http://localhost:8000 in your browser. (Opening index.html directly may show the UI, but service workers require localhost or HTTPS.)

## Install on Android
Publish the folder to an HTTPS static host (GitHub Pages, Netlify, or Cloudflare Pages). Open the site in Chrome on Android, then use the browser menu → Add to Home screen / Install app.

## What's included
- CHELLE, TINKD, Gym, Skate, Cleaning and Family clickable arenas
- Morning mission selection: shipping, shipping+design, design only, free
- Gym, run, and skate switches
- Weekday/Saturday/Sunday shipping rules
- Editable quests and completion XP
- CHELLE notes and reminders with a small wife avatar only in notes
- Device-local saved progress, exportable JSON backup
- Offline service worker after first visit

## Limitations
- Not yet hosted or deployed
- No notifications, cross-device sync, or automated weather
- The small wife icon is an emoji placeholder, not a custom portrait
- Gym every-other-day selection is manual
- Internet required for optional web font; system fallback is provided
