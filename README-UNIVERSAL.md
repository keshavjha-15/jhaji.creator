# jhaji.creator — Universal Download Package

**One ZIP for laptop and mobile.** Extract this ZIP once, then use the matching folder for your device.

## What's inside
- `extension/` — browser extension for laptop Chrome/Edge/Brave and compatible Android extension browsers.
- `pwa/` — installable mobile/desktop web app companion for Android, iPhone, tablets and laptops.
- `PRIVACY_POLICY_TEMPLATE.md` — privacy policy template.
- `BRAND.md` — product branding information.

## Choose your device

### Windows / Mac / Linux laptop — Chrome, Edge or Brave
1. Extract this ZIP.
2. Open the browser extensions page:
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
   - Brave: `brave://extensions`
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select the `extension` folder inside the extracted package (the folder containing `manifest.json`).
6. Open a feedback form, click the extension, scan the page, choose your ratings, preview and apply.
7. Review every answer and submit the form yourself.

### Android phone — live browser extension
1. Use an Android browser that explicitly supports extensions. Browser support varies by product and version.
2. Open that browser's extension manager and follow its supported installation process.
3. If it supports loading a local/unpacked extension, select the `extension` folder from the extracted package.
4. Open the feedback form in that same browser, open jhaji.creator, scan and apply.
5. Review every answer and submit yourself.

**Important:** Standard Chrome for Android does not support desktop Chrome extensions. The extension is not signed or published to a mobile extension store in this package. Some mobile browsers do not permit local extension installation.

### iPhone / iPad — installable PWA
1. Host the contents of the `pwa` folder on a public HTTPS website.
2. Open that HTTPS address in Safari.
3. Tap Share → **Add to Home Screen**.
4. Launch jhaji.creator from your Home Screen.

iPhone users can use the PWA planner. The included Chromium extension does not install in iOS Safari. A true iOS Safari extension requires a separate native Xcode project and App Store submission.

### Android — installable PWA alternative
1. Host the contents of `pwa` on HTTPS.
2. Open the URL in Chrome or another supported browser.
3. Choose **Install app** or **Add to Home Screen**.

## Important capability difference
The browser extension can inspect and update visible, standard HTML `<select>` dropdowns on the active page after the user explicitly scans and applies. It does not support every university form: custom dropdowns, radio buttons, iframes and shadow-DOM controls may not work.

The PWA is a standalone rating planner. A normal PWA cannot read or modify another browser tab. Use the extension in a compatible browser for live form filling.

## Privacy and safety
- No university login credentials are requested.
- No backend, analytics or remote API is included.
- The PWA saves its plan locally on the device.
- The extension only works after the user invokes it on the active page.
- No form is submitted automatically.
- Choose ratings that honestly reflect your own experience and review all answers.

## Public publishing
This is a developer-installable bundle, not a store-approved release. Before public distribution, test on representative forms/devices, complete the privacy-policy placeholders, host the policy on HTTPS, and submit separately to each relevant extension store.
