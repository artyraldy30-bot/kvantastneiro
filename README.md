# GRAND THEFT NEIRO — static site

## Run locally
Open `index.html` in a browser, or use any static web server.

## Google Sheets live statistics
The site is configured for:
- Spreadsheet ID: 1HArOqLr2rFlgn8RDXPF9dRDbYKK2uLfNgzcAlZYZYBY
- Sheet GID: 1974178009

For browser-side live syncing, the sheet must be accessible publicly (or published to the web).
The JavaScript polls the Google Visualization endpoint every 60 seconds.

The parser accepts common layouts such as:
1. rows: `Downtown | 82`
2. columns: `Downtown | Nightlife | Harbor ...` with numeric values
3. header row followed by a numeric data row

If the sheet is unavailable, the site displays demo values rather than breaking.

## Publish
Upload the contents of this folder to any static hosting provider (for example Vercel, Netlify, GitHub Pages, Cloudflare Pages, or your own server). No backend is required for the front-end.
