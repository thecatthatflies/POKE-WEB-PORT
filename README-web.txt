Web Pokémon Battle — How to Run

Option A: GitHub Pages (recommended, works on school Chromebooks)
1) Create a new GitHub repo (private or public).
2) Upload ALL files from this folder (keep the folder structure the same).
3) In the repo: Settings → Pages → set Source to “Deploy from a branch”, pick “main” and “/ (root)”. Save.
4) Wait for Pages to give you a URL. Open it. Play!

Option B: Local web server (if you have Linux or another computer)
- Python: run `python3 -m http.server` in this folder, then visit http://localhost:8000
- Any simple static web server is fine.

Note: Opening index.html directly with file:// might block CSV fetches in some browsers. Use Pages or a simple web server.
