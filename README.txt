FOUNDATION STUDY HUB — PWA FILES

These files are for publishing the app as a website/PWA using GitHub Pages.
They are not an APK.

SECURITY NOTES
- The Android manifest in the source project requests no Android permissions.
- The PWA version does not ask for contacts, camera, microphone, or location.
- Study progress is stored in this browser on this device using localStorage.
- The app files do not need third-party scripts or external APIs to run.
- Publish only through HTTPS (GitHub Pages provides HTTPS).
- A PWA avoids APK sideloading prompts, but it is not a security certification.
- Never ignore browser/device security warnings.

GITHUB PAGES
1. Extract this ZIP.
2. Upload the contents of this folder (index.html, manifest.webmanifest,
   service-worker.js, icon-192.png, icon-512.png, README.txt) to the ROOT
   of the repository named Foundation-study-hub.
3. Commit the files to the main branch.
4. In the repository open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select Branch: main and Folder: /(root), then Save.
7. Wait for GitHub Pages to publish. Open the Pages URL shown there in Chrome.
8. Chrome menu (three dots) > Add to Home screen / Install app.

NOTE: Upload the files inside the extracted folder, not the ZIP itself.
Do not upload icon files from an unknown source. These icons are generated
from the launcher image already included in the supplied project.
