# Mobile Ticket Reader

This is the mobile version of the order ticket reader.

It can:
- take/upload ticket photos from a phone
- OCR the ticket
- break orders into items, seasonings, and temps
- compile totals from multiple tickets
- export CSV

## Easiest mobile use

1. Upload this folder to GitHub Pages, Netlify, or any simple web host.
2. Open the web link on your phone.
3. Tap Share.
4. Tap Add to Home Screen.

Now it opens like an app.

## Local test

Open `index.html` in a browser.

For full phone install behavior, host it online. The OCR uses Tesseract.js from a CDN, so the first load needs internet.

## Customize

Open `index.html` and edit:

```js
const SEASONING_WORDS = [...]
const TEMP_WORDS = [...]
```

Add your restaurant's exact seasonings, sauces, doneness terms, and shorthand.
