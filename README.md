# Focus Timer

Focused work timer with built-in music playback, custom audio uploads, and local productivity tracking in the Northline suite.

## Live Demo
[https://sbdkim.github.io/focus-timer](https://sbdkim.github.io/focus-timer)

![Screenshot](assets/screenshot.png)

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
Open `index.html` in a browser.

## Tests
Open `tests.html` in a browser to run the in-browser checks.

## Deployment Notes
- The repo is set up for GitHub Pages deployment from `main` through GitHub Actions.
- Keep static asset paths relative so the same files work locally and on Pages.

## Privacy / Notes
- All data stays in the browser.
- Media assets are loaded locally and the app does not require sign-in or a backend.
- The public product name is `Focus Timer`, and the repo slug target is `focus-timer`.

## License
MIT
