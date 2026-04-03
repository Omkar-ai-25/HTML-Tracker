# Habit Tracker

A clean, focus-first habit tracker built as a single HTML file.

It is designed to feel simple and non-distracting while still giving useful progress feedback. Open it in Chrome and keep building habits day by day.

## Why this project stands out

- Single file app: no build step, no install, no setup friction
- Smooth and lightweight UI with mobile-first layout
- Works great in modern Chrome
- Saves your habits and progress automatically with local storage
- Data is still there every time you open the app

## Core features

- Create and delete habits quickly
- Mark habits complete/incomplete for today
- Daily streak tracking per habit
- Daily progress bar on the home screen
- Weekly analytics view
- Category-wise completion insights
- Default starter habits to begin immediately

## Built with

- React 18 (UMD)
- Tailwind CSS (CDN)
- Babel Standalone (in-browser JSX transpile)
- Browser Local Storage for persistence

## How to run

1. Download or clone this repository.
2. Open Tracker.html in Google Chrome.
3. Start adding habits and tracking progress.

That is it. No package manager, no terminal commands, no deployment needed.

## Data persistence

This app stores data in your browser using Local Storage.

Stored keys:
- habit-tracker-habits
- habit-tracker-history
- habit-tracker-last-date

Notes:
- Data is saved on your device and stays available on next open.
- If you clear browser storage, tracker data is removed.
- Habit completion status resets when a new day starts.

## Best experience

- Browser: Google Chrome (latest)
- Internet: Required on load (CDN scripts for React, Tailwind, Babel)
- Device: Works on desktop and mobile screens

## Project structure

- Tracker.html: Complete app (UI + logic + storage)

## Roadmap ideas

- Optional export/import backup
- Reminder notifications
- Custom themes
- Monthly trend view

## Contributing

If you have ideas to improve focus, speed, or usability, feel free to open an issue or submit a pull request.

## License

You can add your preferred license here (for example: MIT).
