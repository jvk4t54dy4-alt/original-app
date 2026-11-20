# reset. — free personal lifestyle app

## Included
- Home dashboard
- Habit tracker with +10 XP per completion, +50 daily completion bonus, levels, and streak display
- Calorie and macro tracker with editable targets and manual food entry
- Weekly meal planner and saved meal ideas
- Progress photos saved in browser IndexedDB on this device, side-by-side comparison, and weight log
- Local-first data storage; no account, paid API, subscription, or trial

## Run locally
Open `index.html` in a modern browser. The core app works locally. Browser storage is tied to that browser/device.

## Install on iPhone (free)
For a proper iPhone home-screen web app, the files need to be served over HTTPS:
1. Create a free GitHub account and a new public repository named `reset-app`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the provided HTTPS address in Safari on your iPhone.
6. Tap Share → Add to Home Screen → Add.

GitHub Pages is a free static hosting option for public repositories. No paid plan or free trial is required.

## Important privacy/storage notes
- Habit, nutrition, meal, and weight data are saved in localStorage in the browser.
- Photos are stored as image blobs in IndexedDB in the same browser/device and are not uploaded to a server.
- Clearing Safari website data, deleting the website data, or changing browser/device can remove local data. Export/backup and cross-device sync are not implemented in this starter version.
- For privacy, do not use a shared device/browser profile for personal progress photos.
- The app currently uses manual food entry; it does not use a paid food database or barcode API.
