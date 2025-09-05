# Productivity Dashboard (Vanilla HTML/CSS/JS)

A single-page app with three tools: To‑Dos, Notes, and a Pomodoro timer. No frameworks, no build step, all data is stored in your browser (localStorage).

## Run in IntelliJ IDEA
1. Open IntelliJ IDEA (Community or Ultimate).
2. **File → Open…** and select the project folder `vanilla-productivity-dashboard`.
3. Right‑click `index.html` → **Open in Browser** (or use the built‑in static server if you have one).
   - Alternatively, run a simple server:
     - Python 3: `python -m http.server 8000`
     - Node: `npx http-server .`

## Features
- To‑Dos: add, complete, edit, delete, search, sort by created/due/priority.
- Notes: create, search, edit, delete.
- Pomodoro: configurable durations, auto‑cycle short/long breaks.
- Light/Dark theme toggle.
- Export/Import data to JSON.

## Project Structure
```
vanilla-productivity-dashboard/
├─ index.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ app.js
└─ assets/
   └─ icon.svg
```

## License
MIT – do anything, no warranty.
