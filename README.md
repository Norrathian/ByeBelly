# Gut Check — Lose the Beer Gut

A single-file web app for nutrition, exercise, calorie counting, and waist progress.
No build step, no dependencies, no backend. All data is stored in the browser (localStorage).

## Run it
Open `index.html` in a browser, or enable GitHub Pages on this repo (Settings → Pages → Deploy from branch → main / root).

## Install it like an app (PWA)
Gut Check is a Progressive Web App: it installs to your home screen, opens full-screen, and works offline (your data is in localStorage on the device either way).
- **Android / Chrome:** open the live GitHub Pages URL → tap **Install Gut Check** in the app header (or ⋮ menu → Add to Home screen / Install app).
- **iPhone / Safari:** open the live URL → Share → Add to Home Screen.
- Files that make this work: `manifest.webmanifest`, `sw.js`, `icons/` (SVG + 192/512 PNG + Apple touch icon).
- Note: the PNG icons must be uploaded through github.com (drag-and-drop) — pushing binary files through the GitHub API corrupts them.

## What's inside
- **Today dashboard** — calorie + protein targets (Mifflin-St Jeor, ~500 cal deficit), water tracker, daily plan & tip, Beer Bank (calories + money from beers not drunk)
- **Food & Calories** — searchable built-in food database, meal log, macro bars, quick-add, custom foods
- **Move** — beginner bodyweight Workout A/B with form cues, rest timer, walk/activity log with pace & calorie estimates, exercise library
- **Progress** — weight and waist (the gut metric) logs with trend charts, projected pace, badges, weekly report card, JSON export/import
- **Eat Smart** — high-protein, filling recipes (no fish; shrimp included) that build a grocery list, plus simple gut-loss rules
- **Extras** — Hunger SOS 10-minute timer

## First use
Go to Setup, enter age / height / starting weight / goal weight, save — your daily targets are calculated automatically. Then log your first weigh-in + waist measurement in Progress.

## Pinned for v2 (planned, not in this draft)
- Photo calorie estimation + in-app photo log (attach a meal photo, palm/fist portion guide)
- Progress photos timeline (front/side photos lined up with waist measurements)
- Weekly calorie banking (weekly budget view — bank calories for weekend meals)
- Voice quick-log
- Shareable milestone cards

Not medical advice.
