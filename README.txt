V BUSINESS PRO — PWA / OFFLINE WEBSITE PACKAGE

Files:
- index.html: app interface
- manifest.webmanifest: installable app metadata
- sw.js: offline app-shell cache
- icon-192.png and icon-512.png: app icons

To publish:
1. In GitHub repository V-business-pro, replace index.html with this package's index.html.
2. Upload manifest.webmanifest, sw.js, and both PNG icon files to the repository root (same level as index.html).
3. Commit changes and wait for GitHub Pages to deploy.
4. Open https://yaduvanshivivek563.github.io/V-business-pro/ in Chrome on Android.
5. Chrome menu > Install app (or Add to Home screen).

Offline note:
The service worker caches the app shell. Existing billing/products/customers data remains in this browser's localStorage on that device. This does NOT yet provide Firebase cloud sync, secure accounts, verified UPI payments, or server-enforced subscriptions. Do not treat demo subscription activation as real payment verification.
