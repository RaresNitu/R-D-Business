# Text Analyzer

A single-page, local-only text analyzer. Paste or load text to get live counts (words, characters, sentences, paragraphs), reading-time estimates, and keyword frequencies—no external APIs.

## Run locally
- Double-click `index.html` to open it directly in your browser.
- Or serve the file for consistent clipboard/file access: `python -m http.server 8000` then visit `http://localhost:8000`.

## Share privately
- Zip the folder (or put it on a USB drive) and open `index.html` anywhere. Everything runs offline.

## Publish for others
- Push this repository to GitHub and enable GitHub Pages for the `work` branch to get a shareable link.
- Any static host (Netlify, Vercel, Cloudflare Pages, S3/CloudFront) works—just upload `index.html`.

## Notes
- No backend or API keys are required; all analysis stays in the browser.
- Ideal for quick checks on articles, transcripts, or other long-form documents.
