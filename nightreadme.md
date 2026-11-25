# StudySync

A smart student learning and academic management web app built as a B.Tech CSE project.

## Features
- Registration, login, profile with picture, goals and settings
- Dashboard: study hours, streaks, weekly and monthly progress, heatmap, rank, deadlines
- Study techniques library (10 techniques) with step-by-step guides
- Focus timer: Pomodoro, custom and stopwatch modes, focus mode, saved session history
- Streaks, XP, levels and achievement badges
- Daily, weekly and monthly leaderboard
- Attendance tracker that shows how many classes you can miss or must attend
- Assignment and test tracker grouped by subject
- Light and dark mode, responsive layout

## Tech
Plain HTML, CSS and JavaScript in a single file (`index.html`). No build step. Data is stored in the browser's localStorage.

## Run locally
Open `index.html` in a browser.

## Limitations
Accounts are stored locally and the password hashing is for demonstration only. Leaderboard peers are sample data. A backend (Firebase or Supabase) would be needed for real multi-user accounts.
