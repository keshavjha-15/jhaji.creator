# jhaji.creator v2.0
Publisher: Keshav Kumar.

Package:
- extension/: Chromium Manifest V3 extension for compatible Android browsers and desktop testing.
- pwa/: installable offline-capable mobile planner for Android and iPhone.

## V2 features
Extension: same or individual ratings, visible dropdown scan, filter, confirmation preview, unanswered-only mode, undo last apply, JSON export.
PWA: question templates, editable question labels, individual ratings, local save/restore, JSON import/export, copy summary, offline shell.

## Platform limitations
The PWA cannot read or control other browser tabs. Use the extension only in a mobile browser that explicitly supports extensions. Standard Chrome Android and iOS Safari do not support this extension package. iPhone users can install the PWA; a true iOS Safari extension requires a separate native Xcode project and App Store process.

Extension supports visible standard HTML select controls only; custom dropdowns, radio buttons, iframes, and shadow DOM are not supported. Browser extension support and sideloading rules vary by browser/version.

## PWA install
Host the contents of pwa/ on HTTPS. Open the URL on Android/iPhone. Android: browser menu > Install app/Add to Home Screen. iPhone: Safari Share > Add to Home Screen.

## Extension install/test
Load extension/ unpacked at chrome://extensions on desktop Chrome/Edge with Developer mode. For Android, use a browser with extension support and follow its current extension installation process. This package is not signed or store-published.

No backend, analytics, or auto-submit. Students must choose honest ratings and review answers before submission.
