MILLFIELDS TRUST – EMERGENCY LIGHTING MANAGER (ANDROID PWA)

This package turns the existing web app into an installable Progressive Web App (PWA). The Millfields Trust logo supplied in the conversation is embedded in the app and used for the Android app icon.

IMPORTANT
- A PWA must be served from an HTTPS website to be installable. Opening index.html directly from Downloads will run the web page but will not provide the normal Android install flow.
- This package is ready to publish as a static website (for example, GitHub Pages). Publish the CONTENTS of this folder, not the ZIP itself.
- Once published, open the HTTPS address in Chrome on Android, tap the three-dot menu, then choose “Install app” or “Add to Home screen”. The wording varies by Chrome version.
- The current app stores records in the browser's local storage. Installing it does not automatically synchronise data between phones or users. Use the same installed app/browser profile to access the same local records. Export backups regularly.
- The Excel export currently loads its XLSX library from jsDelivr, so exporting to Excel needs an internet connection.

FILES
- index.html: app with PWA registration and existing embedded Millfields Trust logo
- manifest.webmanifest: app name, colours and icons
- sw.js: service worker for offline app shell caching
- icon-192.png / icon-512.png: Android app icons made from the supplied logo
- apple-touch-icon.png: touch icon

This is an installable web app, not a signed standalone APK. A signed APK would require a separate Android build/signing process.
