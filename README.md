# English Learning Hub

A lightweight, responsive English-learning website with Malayalam and Hindi support.

## Features
- 12-week English learning roadmap
- Seven complete Week 1 lessons (four core topics, extended sentence building, common mistakes, and a review)
- Browser-based progress checklist (localStorage)
- Personal grammar questions notebook (localStorage)
- Responsive layout for desktop and mobile
- No framework, build step, backend, or account required

## Run locally
Open `index.html` in any modern browser. All files are static.

To serve with Python instead:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000/`.

## Publish on GitHub Pages
1. Create a new repository (for example, `english-learning-hub`).
2. Upload `index.html`, `styles.css`, and `app.js` to the repository root.
3. In repository Settings > Pages, choose `Deploy from a branch`, select `main` and `/ (root)`, and save.
4. Wait for GitHub to provide a published website URL.

## Important
Progress and saved questions are stored locally in the current browser, not synced to GitHub or between devices. Clearing browser storage erases them.

Course lessons are informational. Practice quizzes are deliberately omitted until requested. Lesson understanding can be marked separately; the first four lesson checkmarks also update the Week 1 roadmap.