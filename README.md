# Henesys AA Repair

Marketing site for Henesys AA Inc., a garage door repair and installation company serving Massachusetts. Live at [henesysaarepair.com](https://henesysaarepair.com).

## Structure

The entire site is a single static file: [`index.html`](index.html). No build step, no dependencies — HTML, CSS and vanilla JS all inline, plus a Google Fonts stylesheet link.

## Local preview

Serve the folder with any static file server, for example:

```bash
npx serve .
```

Then open the printed local URL in a browser.

## Deployment

Static hosting only — point your host at `index.html`. No environment variables or backend are required.
