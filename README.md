[README.md](https://github.com/user-attachments/files/30963075/README.md)
# Send It — Disc Golf Drive Log

A single self-contained file: `index.html`. No build step, no dependencies to install.

## Put it on GitHub Pages

1. On github.com, create a new repository (public or private both work for Pages on a free account, though private repos need a paid plan for Pages — public is simplest).
2. Upload `index.html` to the repo root (Add file → Upload files works fine from the browser, no git command line needed).
3. Go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)`. Save.
5. GitHub gives you a URL like `https://yourusername.github.io/your-repo-name/` — it takes a minute or two to go live after the first save.

## On your phone

- Open that URL in Safari (iOS) or Chrome (Android).
- When it asks for location permission, allow it — that's what powers the GPS distance tracking.
- Optional: use "Add to Home Screen" (Safari share sheet, or Chrome's menu) to get an icon that opens it full-screen like a regular app.

## Your data

Everything (your disc bag, session history, unit preference) is saved in the browser's local storage on your phone, tied to that specific URL. It stays put across visits, but it's local to that browser — it won't sync to another device, and clearing Safari/Chrome site data would wipe it. If you want it to survive a phone swap, there's no export button yet, but the data's just JSON in local storage if you ever want one added.

## Updating it later

Edit `index.html` (in the GitHub web UI's editor, or clone the repo and edit locally) and commit — Pages redeploys automatically within a minute or so.
