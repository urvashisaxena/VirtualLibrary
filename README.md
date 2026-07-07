# The Reading Room — a Virtual Library

A cozy, old-English-library virtual bookshelf for a rainy day. Two shelves —
**Books I Have Read** and **To Be Read** — rendered as book spines on dark
wooden shelves, beside a rain-streaked window.

## Running it

No build, no server, no dependencies. Just open the file:

1. Download or clone this repository.
2. Double-click `index.html` (or open it in any modern browser).

## Using it

- Click **✦ Add a Book** next to either shelf and type the book's title and
  (optionally) its author.
- Click a book on a shelf to open it: **catalog your favourite lines and
  annotations** (a red ribbon appears on the spine of any book that holds
  them), **mark it as read**, **move it back to To Be Read**, or **remove** it.
  In the annotation box, Ctrl/Cmd+Enter also inscribes the line.
- **Drag a book** to rearrange it on its shelf, or drop it onto the other
  shelf to move it.
- Click **☂ Rain** in the top-left corner to hear a soft rain patter,
  generated in the browser with the Web Audio API — no audio files needed.
- Your books, authors, ordering, and annotations are saved in your browser's
  `localStorage`, so everything stays local to your machine and is still
  there next time you open the page.

Each book's spine colour, height, and width are derived from its title, so
your shelf always looks the same — like a real bookshelf.
