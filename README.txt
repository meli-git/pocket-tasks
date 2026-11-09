POCKET TASKS — PINK EDITION

This is a small installable web app for iPhone. It stores tasks locally in the browser on your device.

PUBLISHING / UPDATING ON GITHUB PAGES
1. Extract this ZIP.
2. Open your existing pocket-tasks repository on GitHub.
3. Choose Add file > Upload files.
4. Upload and replace the files in the repository root with these updated files. Make sure index.html, manifest.webmanifest, sw.js and both icon files are at the root (not inside another folder).
5. Commit the changes. GitHub Pages will publish the update.
6. Open your existing GitHub Pages address. If the old design remains, close the app completely, open the site in Safari, refresh, and then reopen the Home Screen app. The service worker cache has been versioned to refresh the app shell.

INSTALLING ON IPHONE
Open the HTTPS GitHub Pages address in Safari > Share > Add to Home Screen. Enable Open as Web App if offered.

DATA
Tasks are stored in localStorage on this device/browser. This update keeps the same storage key, so existing tasks should remain on the device. Export a backup before making changes as a precaution. Clearing Safari website data may erase tasks. This app does not sync between devices.
