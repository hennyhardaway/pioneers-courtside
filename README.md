# Pioneers Courtside

A custom basketball stat tracker for the North Miami Pioneers, designed for a team manager on an iPad in landscape and for court-first entry on a phone.

## Run

Open `index.html` in a modern browser, or serve this directory with any static web server. There is no build step. GitHub Pages can serve `index.html` from the repository root.

## Features

- Player-first and stat-first entry with quick popups.
- Shot locations, made/missed baskets, And 1, and shooting-foul free-throw sequences.
- Paint touches, deflections, forced turnovers, and standard basketball stats.
- Multiple-player substitutions and optional scoreboard timestamps for player minutes.
- Quarter transitions, scorekeeping, timeout tracking, corrections, and grouped Undo/Redo.
- Box scores, shot charts, season views, backups, and social score/player cards.

## Data and dependencies

Recorded games, rosters, and player photos are stored in the browser on each device. Publishing this source does not export those records. Use the app's backup/export controls to transfer or preserve game data.

The app loads fonts from Google Fonts and the SheetJS XLSX browser library from cdnjs for spreadsheet exports. Team imagery is embedded in the HTML. Some file-saving features depend on the browser or host environment.

## Team definitions

- Paint touch: a half-court dribble entry with both feet in the paint; each re-entry counts.
- Deflection: a defensive touch disrupting the ball, without requiring a possession change.
- Forced turnovers include steals and charges; linked credits count once.
- A missed shot on a shooting foul normally does not count as an FG attempt; a made And 1 does.

## Source layout

The current application is a standalone `index.html` with embedded CSS, JavaScript, and team assets. Hosting credentials and deployment configuration are not included.

This repository does not grant a separate open-source license or permission to reuse North Miami team branding.
