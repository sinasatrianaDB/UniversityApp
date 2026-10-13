UNIVERSITY PLANNER PWA

PACKAGE CONTENTS
- index.html: planner app
- manifest.webmanifest: installation metadata
- service-worker.js: offline support
- icons/: Android app icons

IMPORTANT
The PWA must be hosted via HTTPS. Opening index.html directly or previewing it in SharePoint will not activate installation/offline functionality.

QUICK TEST ON A COMPUTER
1. Extract this ZIP.
2. In the extracted folder, run a local web server, for example:
   python -m http.server 8080
3. Open http://localhost:8080 in Chrome or Edge.

ANDROID INSTALLATION AFTER HTTPS DEPLOYMENT
1. Open the published HTTPS address in Chrome on Android.
2. Open the Chrome menu.
3. Select "Install app" or "Add to Home screen".
4. Launch Uni Planner from the Android Home screen.

DATA
Completed milestones are stored locally in the browser/device using localStorage.
