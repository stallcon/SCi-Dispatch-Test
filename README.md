# SCI Dispatch App

This repository is ready to upload to GitHub and publish with GitHub Pages.

## Files included
- `index.html` — the current app build
- `icon-192.png` — app icon
- `icon-512.png` — app icon
- `favicon.png` — favicon
- `site.webmanifest` — installable web app manifest
- `.nojekyll` — prevents GitHub Pages processing issues

## Suggested repository name
`SCI-Dispatch-App`

## How to publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. In GitHub, open **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, set:
   - **Source** = `Deploy from a branch`
   - **Branch** = `main`
   - **Folder** = `/ (root)`
6. Save.
7. Wait for GitHub Pages to publish.
8. Open the live Pages URL GitHub gives you.

## Optional next steps
- Add a real shared backend for multi-user testing.
- Replace browser/local-storage persistence with cloud database storage.
- Add domain name and HTTPS redirect.
- Add server-side auth.

## Current built-in logins
- Customer example: `CUST1001` / `ready123`
- Dispatcher: `dispatch01` / `dispatch123`
- Driver: `driver03` / `driver123`
- Admin: `admin01` / `admin123`
