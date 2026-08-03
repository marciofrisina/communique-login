# Communique — Animated Login

## Technology

Standalone **HTML, CSS, and vanilla JavaScript** implementation. It has no React, Vue, external-library, or server dependency for the animation.

The `Alumni Sans Pinstripe` heading font is loaded from Google Fonts; the remaining interface works without external dependencies.

## Files

- `orbital-particles.html` — complete page, styles, Canvas animation, and form behavior.
- `communique-logo-336.webp` — transparent, optimized logo asset used by the page (336 × 212 px, suitable for the 168 × 102 px display area at 2× pixel density).
- `release-notes.html` — starter page for the current version's release notes.

## How to open

Open `orbital-particles.html` directly in any modern browser. The animation is responsive and fills the available viewport.

## Project integration

1. Copy the HTML as-is, or split it into a component, stylesheet, and JavaScript module to match the application architecture.
2. Keep `communique-logo-336.webp` at the same relative path as the HTML, or update the image `src` attribute.
3. Replace the demonstration submit behavior with a call to the real authentication endpoint.
4. Connect the `#recover` and `#signup` links to the appropriate routes.
5. Replace the placeholder content in `release-notes.html`, or point the release-notes icon to the application's update route.

## Authentication note

The form only validates its fields in the browser and does not send credentials to a server. Authentication integration belongs to the main application/backend.
