# Hoosier Experience Record

Clickable prototype of Indiana University Bloomington's Hoosier Experience Record, a Credential Connections credential page.

Open `index.html`, or turn on GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/`) to get a shareable link.

## What's in it

- `index.html`: the page, exported from the Claude Design canvas "Hoosier Experience Record".
- `support.js`: the runtime that draws the page. Keep it next to `index.html`.
- `assets/`: header lockup, campus background and the record seal.

## Prototype controls (don't build)

The frosted panel on the right switches between desktop and mobile. The × collapses it to a tab; Shift+H hides it.

## Notes for development

- Each term and course header is a real `<button>` with `aria-expanded`; collapsed panels are hidden from keyboard and screen readers.
- "Visit website" is a link (styled as the CC secondary button) to https://cecredential.iu.edu/validation/index.html and opens in a new tab.
- On mobile, Student Record Details stacks each label above its value.
