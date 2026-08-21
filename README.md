# PS5 Browser Search

A lightweight, dark-themed start page for the **PlayStation 5 Internet Browser**.
Single self-contained `index.html` — no build step, no server, no tracking.

![Platform](https://img.shields.io/badge/platform-PS5-blue) ![License](https://img.shields.io/badge/license-GPL--3.0-green)

## Features

- **Smart address bar** — full URLs open directly; anything else is sent to [DuckDuckGo](https://duckduckgo.com) as a search query (missing `http://` is added automatically).
- **Favorites** — save sites from the search bar or from history, with duplicate protection.
- **History with deduplication** — revisiting a site moves it to the top instead of creating duplicates; capped at 50 entries.
- **PS5-friendly UI** — large touch/gamepad targets, high-contrast dark theme, tuned for the PS5's WebKit engine.
- **Fully local** — favorites and history are stored in the browser's `localStorage`. Nothing leaves your console.

## Usage

1. Open the page in the PS5 Internet Browser:
   `https://kvnhrt.github.io/ps5-browser-search/`
2. Type a URL (`youtube.com`) or a search phrase (`best ps5 games`) and press **Open**.
3. Press **Fav** to save the current input as a favorite, or use **Save** on any history entry.

Tip: set the page as your bookmark or browser start page for quick access.

## Notes

- The page auto-migrates old saved data to the current storage format.
- Best experienced on the PS5 browser; it also works fine on desktop browsers for testing.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).
