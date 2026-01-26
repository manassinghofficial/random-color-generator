# Color Generator

A small static web page that generates a random RGB color, applies it as the page background, and shows the RGB value.

## Features

- Generates a random `rgb(r, g, b)` color
- Updates the page background to the generated color
- Displays the generated RGB value on the page
- Copies the generated RGB string to the clipboard

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript

## Setup & Run Instructions

1. Clone or download this repository.
2. Open `index.html` in a browser.

Notes for clipboard behavior:
- Clipboard copying via `navigator.clipboard` typically requires a secure context (`https://`) or `http://localhost`.
- If you open the file directly (e.g., `file://`), clipboard copying may be blocked by the browser.

- If you use VS Code, the “Live Server” extension works well.

## Notes

This is a personal learning/practice project focused on basic DOM manipulation, events, styling, and browser APIs. It is not intended to be production-ready.

