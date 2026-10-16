# APAC Visitor Check-In — Browser Demo

This is a static, browser-based **demonstration** of the APAC Visitor Check-In system. It is not connected to the production Android app. All entered records exist only in JavaScript memory on the currently open page and disappear when the page reloads or closes. Do not enter actual visitor personal information.

Features: four visitor types; check-in; optional appointment date/time; sign-out; live clock; 60-second inactivity reset to welcome screen; demonstration administrator view, roster, history, and CSV export. There is no photo capture.

## Publish with GitHub Pages

1. Create a **new public repository** (for example `apac-visitor-demo`). Do not change the existing private Android repository.
2. Upload `index.html` and `apac_logo.png` to the root of the new repository (upload the extracted files, **not the ZIP**).
3. Under repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save.
4. GitHub will show the live URL once the deployment completes, usually `https://YOUR-USERNAME.github.io/apac-visitor-demo/`.

Privacy/security: GitHub Pages makes the published site public. The site has no server-side access control, shared database, real administrator authentication, or durable storage. The demo is not appropriate for operational or regulated visitor data. An actual shared deployment requires authenticated hosting, secure centralized storage, retention and privacy policies, and access controls.
