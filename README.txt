MY MONEY TRACKER — iPHONE + WINDOWS WEB APP

WHAT THIS PACKAGE DOES
- Makes the existing tracker installable from Safari on iPhone and from Chrome/Edge on Windows.
- Supports the same expense, card, bank, loan and reporting features as the original HTML tracker.
- Supports app-style launch and basic offline shell caching once first opened online.

IMPORTANT DATA LIMITATION
The current tracker saves data in the browser on each device. It does NOT automatically sync between iPhone and Windows yet. Use Backup / Settings > Download full backup (JSON) and Restore backup JSON to move data manually. Do not assume this is a cloud backup.

HOW TO PUBLISH IT SO BOTH DEVICES CAN OPEN THE SAME LINK
1. Create or open a GitHub repository for the app.
2. Upload all files in this folder to the repository root (index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png).
3. In the repository, open Settings > Pages.
4. Under Build and deployment, select Deploy from a branch; choose the main branch and /(root), then Save.
5. Wait for GitHub Pages to publish. It will give you an HTTPS URL. Open that exact URL on both devices.

INSTALL ON IPHONE
1. Open the published HTTPS URL in Safari (not an in-app browser).
2. Tap Share.
3. Choose Add to Home Screen. If offered, enable Open as Web App.
4. Tap Add.

INSTALL ON ANDROID
1. Open the published HTTPS URL in Chrome on your Android phone or tablet.
2. Tap the browser menu (three dots) and choose Install app or Add to Home screen. The wording can vary by Android version.
3. Confirm Install/Add. Open My Money Tracker from your Home Screen or app drawer.

INSTALL ON WINDOWS
1. Open the same HTTPS URL in Chrome or Edge.
2. Use the install icon in the address bar, or browser menu > Install page as app.
3. Pin the app to the taskbar or create a desktop shortcut if offered.

TO MAKE DATA AUTOMATICALLY SYNC
A shared online database and sign-in system must be added in a later version (for example, Firebase or Supabase). Hosting this package alone does not synchronise financial records. Keep JSON backups until cloud sync has been implemented and tested.
