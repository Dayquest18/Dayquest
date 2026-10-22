# DAYQUEST v3 — Pokémon-style world map

This update retains the working v2 morning planner, daily list, clickable arenas and notes. It adds a top-down pixel-art village with six tappable locations, plus a brown-and-white Brittany spaniel pixel sprite. No XP, levels, checkboxes or achievements. Wife character remains only in Notes & Reminders.

## Upload to GitHub Pages

1. Extract ZIP. Upload **all files** in this folder to the root of your existing `Dayquest` GitHub repository, replacing same-name files. **New files**: `world.svg` and `brittany.svg`.
2. Commit changes. Wait for GitHub Pages deployment.
3. Test https://dayquest18.github.io/Dayquest/?v=3 in Safari. Close/reopen the Home Screen app. If still cached, follow previous backup and reinstall steps; do not delete app data without copying notes first.

## Storage and limits

Daily choices and notes are saved in localStorage under `dayquest-v2` for continuity. They are not synchronized or backed up. No push notifications. World map uses responsive HTML buttons overlaying an SVG image; the buttons are accessible and tap-friendly.
