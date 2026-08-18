# Kruti Dev 010 Typing Master

A dark-mode Hindi typing practice web app for the Kruti Dev 010 keyboard layout.

**Live demo:** [ranjan-builds.github.io/KrutiDev-Typing](https://ranjan-builds.github.io/KrutiDev-Typing/)

## Features

- Structured Kruti Dev typing lessons
- Timed speed tests and exam mode
- Free typing practice
- On-screen virtual keyboard and character chart
- Live WPM, accuracy, error, XP, and streak tracking
- Optional sound and vibration feedback
- Installable PWA with offline support
- Social sharing metadata and Open Graph preview image

## Run locally

Serve the project folder using any local web server. Do not open `index.html` directly, because service workers require `localhost` or HTTPS.

For example, with VS Code, install and run the **Live Server** extension. Then open the local URL it provides.

## Project structure

```text
├── index.html              # Application UI, styles, and logic
├── Krutidev.ttf            # Kruti Dev font used for typing text
├── manifest.webmanifest    # PWA application manifest
├── sw.js                   # Offline service worker
├── og.png                  # Social-media sharing preview image
└── icons/icon.svg          # App icon
```

## Deploy to GitHub Pages

1. Push these files to the repository's publishing branch (usually `main`).
2. In GitHub, open **Settings → Pages**.
3. Select **Deploy from a branch**, then choose the branch and the `/ (root)` folder.
4. Save and wait for GitHub Pages to publish the site.

The project is configured for:

`https://ranjan-builds.github.io/KrutiDev-Typing/`

## PWA installation

After deployment, open the live site in a modern browser. The **Install App** button appears when the browser offers installation.

On iPhone/iPad, use Safari's **Share → Add to Home Screen** option.

## Note about Kruti Dev

Kruti Dev is a legacy font encoding. It renders English keyboard keystrokes as Hindi glyphs; it does not convert normal Unicode Hindi text automatically.
