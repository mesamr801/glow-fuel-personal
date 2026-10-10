# Glow & Fuel — Personal Routine Tracker

A lightweight, responsive personal habit and nutrition tracker inspired by the supplied screenshots, with a cleaner interface. It is a static web app: no build tools, account, or server required.

## Features
- Daily routine checklist and custom tasks
- Normal, Tough, Free-eat, and Day-off modes
- Food log with calories and protein; carb, fat, and fibre display areas
- Editable calorie and protein targets
- Water and step tracking
- Daily reading checklist
- Progress dashboard and recent consistency chart
- JSON export/import backup
- Responsive layout for phone and desktop

## Run locally
1. Download or unzip this project.
2. Open `index.html` in a modern browser.
3. Your data is saved in that browser using `localStorage`.

For best results, use a simple local server (optional). If Python is installed, run `python -m http.server 8000` in the project folder, then open `http://localhost:8000`.

## Publish on GitHub Pages
1. Sign in to GitHub and create a new repository, e.g. `glow-fuel-personal`.
2. Upload `index.html` and `README.md` to the repository root (or use **Add file → Upload files**).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub to publish the site. The Pages URL will appear on that settings screen.

## Important storage note
This starter version stores information locally in the browser. Your phone and computer will have separate data. Use **Export** on one device and **Import backup** on the other to move data manually. Publishing to GitHub does not upload the data you enter into the app. For automatic sync across devices, add a private cloud database/authentication layer in a later version.

## Privacy
The app does not intentionally send your entered routine, food, or progress data to a server. Avoid using a shared/public computer for private tracking. Browser storage can be removed if you clear site data, so export backups periodically.

## Current scope
The food logger currently asks for food name, calories, and protein. The carb/fat/fibre display fields are included in the interface but are not yet editable through the food form. This can be expanded in a next iteration.
