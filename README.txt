SYLLABUS TRACKER

Files:
- index.html: app
- manifest.json: installable PWA settings
- sw.js: offline cache

To publish free:
1. Create a public GitHub repository named syllabus-tracker.
2. Upload these three files to the repository root.
3. Open Settings > Pages.
4. Choose Deploy from a branch, branch main, folder /(root), then Save.
5. Open the published HTTPS link in Chrome on Android.
6. Chrome menu > Add to Home screen / Install app.

Morning reminder note:
This version can show a browser notification while the app is open and permission is granted. It cannot guarantee a scheduled notification after Android closes the app. Reliable closed-app scheduled reminders need a push service/backend.
