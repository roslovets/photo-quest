# Photo Quest

A simple photo quest for kids: an adult hides cards around the house or outside, and the child finds them by looking at
photos of the places.

The site works as a small standalone app: no server, no database, and no external libraries. Photos are saved only in
the browser on the device.

## How to Play

1. Print the cards and cut them out.
2. Open `index.html` or the published page.
3. Add photos of the places where you will hide the cards.
4. Tap `Prepare game` and lay out the cards using the prompts.
5. Give the device to the child and start the game.

## Printable Cards

The cards are in [cards.png](cards.png). Open the file separately, print it, and cut along the white gaps.

![Printable quest cards](cards.png)

For printing, A4 with `Fit to page` usually works well.

## Running

The simplest option:

1. Download the project.
2. Open `index.html` in a browser.

To install it as an offline PWA, use `localhost` or HTTPS:

```bash
python -m http.server 5180
```

Then open `http://127.0.0.1:5180/`. After the first load, the app can open without an internet connection.

## What's Inside

- `index.html` — the whole app.
- `manifest.webmanifest` — PWA settings.
- `sw.js` — offline cache.
- `cards.png` — printable cards.
- `icons/` — app icons.
