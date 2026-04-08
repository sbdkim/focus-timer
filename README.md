# Focus Timer

A focused work timer with built-in audio playback, custom uploads, and local productivity tracking.

## Live Demo
[https://shinbum-focus-timer.vercel.app/](https://shinbum-focus-timer.vercel.app/)

## Key Features
- Pomodoro and count-up timer modes
- Configurable focus, short break, and long break durations
- Built-in looping music plus local audio uploads
- Play, pause, reset, skip, volume, and mute controls
- Local session history, daily totals, streaks, and a 7-day activity chart
- Keyboard shortcuts and persisted theme preference

## Tech Stack
- Vanilla HTML, CSS, and JavaScript
- HTML5 Audio and video
- `localStorage` for settings and history persistence

## Setup / Run Locally
Open `index.html` directly in a browser, or serve the repo with a lightweight static server such as `python -m http.server`.

## Tests
Open `tests.html` in a browser to run the in-browser checks.

## Deployment Notes
- Production deploys are served from Vercel at `https://shinbum-focus-timer.vercel.app/`.
- Pushes to `main` trigger automatic production deploys through the Vercel Git integration.
- Static asset paths stay relative so the same files work locally and on Vercel.


## Branding / Theme Notes
- This project uses the Northline product-family shell language for its public-facing page.
- First visit defaults to light mode; dark mode is an explicit user choice and persists locally.
- Shared shell decisions should stay consistent with the current Northline header/topbar, title scale, spacing, and surface model.

## Project Layout
- `index.html` main application entrypoint
- `css/` timer styling and layout rules
- `js/` timer, stats, and audio behavior
- `assets/` screenshots and bundled media assets
- `tests.html` browser-based regression checks

## Notes
- All timer data stays in the browser.
- Media assets are loaded locally and the app does not require sign-in or a backend.
- The public product name is `Focus Timer`, and the repo slug target is `focus-timer`.

## License
MIT
