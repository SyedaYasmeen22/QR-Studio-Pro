# QR Studio Pro

A private, browser-only QR code generator. Everything runs locally: nothing is uploaded and there is no tracking. It is a single static file (`index.html`) with the QR library built in, so there is no build step.

## Features
- Types: URL, text, phone, email, SMS, WhatsApp, location, Wi-Fi, vCard
- Design: colors, gradient, transparent background, dot and eye styles, presets, error correction L/M/Q/H, size, margin, center logo
- Scan-safety warnings (contrast, inverted colors, small margin, logo)
- PNG and SVG download
- Local library (search, load, delete) stored in this browser only; Wi-Fi passwords and logos are never saved
- Light and dark themes

All codes are **static**: the content is fixed once the code is shared or printed.

## Put it on GitHub with VS Code
1. Unzip this folder and open it in VS Code (File > Open Folder).
2. Open Source Control (Ctrl+Shift+G), click **Initialize Repository**, type a message such as "Initial commit", and commit.
3. Click **Publish Branch**, sign in to GitHub if asked, and choose a **public** repository (free GitHub Pages needs public unless you have a paid plan).

## Deploy to GitHub Pages
1. On GitHub, open the repository > **Settings** > **Pages**.
2. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then Save.
3. After a minute the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Run locally
Open `index.html` in a browser, or use the Live Server extension in VS Code.

## Known limitations
No bulk CSV/ZIP generator, camera scanner, offline PWA or automated tests yet.
