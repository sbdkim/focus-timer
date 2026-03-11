# productive-timer

Focused work timer with a built-in looping music deck, custom audio uploads, and local productivity tracking.

Live demo: https://sbdkim.github.io/productive-timer

![Screenshot](assets/screenshot.png)

## Features
- Pomodoro and Count Up timer modes
- Configurable focus, short break, and long break durations
- Built-in default MP3 loop plus custom local audio upload
- Play, stop, seek, mute, and volume controls
- Dark mode by default with a persisted light mode toggle
- Local session history, daily totals, streaks, and a 7-day activity chart
- Keyboard shortcuts for timer control and theme switching
- Browser-only persistence with no backend or sign-in

## How to Use
1. Open `index.html` in a browser.
2. Press `Play` in the music deck if you want the built-in loop.
3. Choose `Pomodoro` or `Count Up`.
4. Adjust focus and break lengths if needed.
5. Press `Start` to begin your session.
6. Use `Pause`, `Reset`, or `Skip` as needed while you work.
7. Review your daily totals and recent session history in the lower panel.

## Tech Stack
- Vanilla HTML, CSS, and JavaScript for a zero-build GitHub Pages deployment
- Google Fonts for typography
- HTML5 Audio for built-in and uploaded music playback
- `localStorage` for settings and session persistence

## Local Development
Open `index.html` in a browser.

## Deploying to GitHub Pages
1. Push the `main` branch to `https://github.com/sbdkim/productive-timer`.
2. Open the repository on GitHub.
3. Go to `Settings` -> `Pages`.
4. Set `Source` to `GitHub Actions`.
5. Push future changes to `main`.
6. Watch the deploy job under `Actions`.
7. Open `https://sbdkim.github.io/productive-timer` once the workflow finishes.

## Notes
- The bundled MP3 is loaded lazily after user interaction so the app shell stays responsive.
- The bundled MP3 is large, so if you want faster clone times later, we can swap it for a shorter compressed track without touching the app logic.
- If you later want cloud sync, this project can be extended without changing the timer UI model.

## License
MIT
