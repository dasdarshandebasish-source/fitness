IPHONE INSTALLATION — DEBASISH DISCIPLINE DASHBOARD
===================================================

RECOMMENDED METHOD: GITHUB PAGES

1. Sign in to GitHub on your Mac.
2. Create a new repository, for example:
   discipline-dashboard
3. Upload ALL files from this folder:
   - index.html
   - manifest.webmanifest
   - sw.js
   - apple-touch-icon.png
   - icon-192.png
   - icon-512.png
4. Open the repository's Settings.
5. Open Pages under Code and automation.
6. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
7. Save and wait for GitHub to provide the website URL.

ON THE IPHONE

1. Open the GitHub Pages URL in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Turn on Open as Web App if shown.
5. Tap Add.

The Discipline icon will appear on the iPhone Home Screen.

OFFLINE USE

After the hosted dashboard has loaded successfully once, the package is designed
to cache its files for later offline use. Entries and checkboxes are stored locally
on that particular device.

IMPORTANT SYNC LIMITATION

Mac and iPhone browser storage do not automatically sync. Use:
Tracker > Export progress JSON
and save the backup to iCloud Drive. Import it on the other device when needed.

PRIVACY

The default dashboard files are placed on the hosting service. Meals, checkboxes,
weight, blood pressure, notes, and other entries remain in the browser's local
storage and are not written back to the static GitHub repository by this app.
