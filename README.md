# BhashaBridge - Languagetranslator Project

This project is a static web-based English-to-Hindi translator app built with HTML, CSS, and JavaScript.

## Main file

- `Languagetranslator.html` — the translator app page.

## Features

- English input textarea with a 500-character limit.
- Hindi translation output panel.
- Quick phrase buttons for common English phrases.
- Real-time character count.
- Copy translation to clipboard.
- Clear input/output button.
- Translation statistics: number of translations, total characters, and total words translated.
- Animated loading shimmer while fetching translations.
- Responsive layout for smaller screens.

## How to run

1. Open `Languagetranslator.html` in a web browser.
2. Type or paste English text into the left panel.
3. Click `Translate to Hindi` to fetch a translation.
4. Use the `✕ Clear` button to reset the form.
5. Click the copy icon to copy the Hindi output.

## Translation source

- The app uses the MyMemory translation API endpoint:
  `https://api.mymemory.translated.net/get?q=...&langpair=en|hi`

## Notes

- This is a static page and does not require a build process.
- If the browser blocks the translation API request, try running the app from a local web server or check your browser's network/security settings.
- The file includes inline CSS and JavaScript, so no separate CSS or JS files are required for `Languagetranslator.html`.
