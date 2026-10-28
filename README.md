# Chore Tracker

A simple, beautiful personal chore tracker that lives on your phone or computer. No account, no subscription — just download and use.

<img width="1462" height="1720" alt="Screenshot 2026-10-28 114202" src="https://github.com/user-attachments/assets/772ba0de-90f5-4d64-86ca-01a6f09b253d" />

## Features

- 📋 **Frequency columns** — organize chores by how often they reset (weekly, monthly, quarterly, custom)
- ✅ **Smart To Do tab** — all unchecked chores sorted by urgency, overdue items first
- 🔄 **Auto-resets** — chores reset themselves when their interval is up
- ↕ **Drag & drop** — reorder chores and columns
- 📴 **Offline** — works without internet after first load
- 📱 **Add to Home Screen** — feels like a native app, no App Store needed

## How to deploy

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. The site deploys automatically on every push to `main`

Your landing page will be at `https://<your-username>.github.io/<repo-name>/`  
The app itself is at `https://<your-username>.github.io/<repo-name>/chore-tracker.html`

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing/demo page with download button and install instructions |
| `chore-tracker.html` | The standalone app — this is what users download |
| `.github/workflows/deploy.yml` | GitHub Actions auto-deploy to GitHub Pages |

## No secrets required

Unlike the Firebase-backed version, this is a fully static site with no API keys or secrets. The app stores all data in the browser's `localStorage` — nothing leaves the user's device.
