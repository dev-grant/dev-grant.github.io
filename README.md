# Life Dashboard

A minimal, TV-friendly dashboard that embeds a published Google Sheets view. Built with Tailwind CSS via CDN. No custom JavaScript is required; the page is a fullscreen iframe that works well with Fully Kiosk Browser on Android TV.

## Features

- Full-screen, responsive iframe that fills the viewport
- Minimal dark styling for TV viewing
- Ideal for use with Fully Kiosk Browser (Android TV) for auto-reload, screensaver, and kiosk features

## Usage

Open `index.html` via GitHub Pages as usual, e.g. `https://<username>.github.io/`.

### URL options

There are no special URL parameters needed; configure kiosk options in your TV app (e.g., Fully Kiosk Browser).

## Change the embedded sheet

Edit `index.html` and update the `src` on the `<iframe id="sheet">` to your Google Sheets published URL.

To publish a Google Sheet:

1. File → Share → Publish to web → Link → Sheet → Web page → Publish
2. Copy the generated link and use it as the iframe `src`

## TV tips

- Use a modern browser (Chromium/Chrome/Edge/Firefox) or Fully Kiosk Browser on Android TV
- For Fully Kiosk Browser: enable fullscreen, "keep screen on" as needed, and set periodic auto-reload if your sheet updates
- For minimal burn-in risk, prefer darker themes and keep screen savers enabled when possible

## Local development

You can view the page by opening `index.html` in your browser or by serving the folder with any static server.
