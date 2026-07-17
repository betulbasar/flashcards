# 🗂️ Flashcards

A small, self-contained flashcard web app. Organize cards into subject folders (Math, History, vocabulary…), then study them one at a time — click a card to flip it over and reveal the answer.

No frameworks, no build step, no server: the whole app is a single `index.html`.

## Features

- **Subject folders** — keep each subject's cards separate; create, open, and delete folders from the home screen
- **Create cards** — front (question) and back (answer), with a handwritten index-card look; `Ctrl+Enter` adds a card quickly
- **Study mode** — one card at a time with a 3D flip on click, previous/next navigation, progress counter, and shuffle
- **Keyboard shortcuts** — `←` / `→` to move between cards, `Space` to flip
- **Saves automatically** — your folders and cards persist in the browser (localStorage), so they're still there next visit
- **Light and dark theme** — follows your system preference

> Note: cards are stored in your browser, not on a server. Clearing site data deletes them, and they don't sync between devices.

## Run it locally

Just open `index.html` in a browser — that's it.

## Deploy with GitHub Pages

This repo is ready for GitHub Pages (the app is a single static file):

1. Push this repository to GitHub.
2. On GitHub, open the repo and go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
5. Wait a minute or two — your site goes live at:

   ```
   https://<your-username>.github.io/flashcards/
   ```

Every push to `main` redeploys the site automatically.
