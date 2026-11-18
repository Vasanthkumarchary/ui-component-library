# UI Component Library

An offline, browsable library of 6,014 community-made HTML + CSS UI components:
buttons, forms, cards, loaders, backgrounds, pop-ups, toggles, and more. Every
preview runs from files in this repository.

## Run it

```bash
python -m http.server 8000
```

Then open http://localhost:8000/library/ . Search, browse by group, and open an
item to see its live preview and code. Saved picks stay in your browser.

## Layout

- `library/index.html` — the viewer
- `data/library.json` — catalog (name, author, group)
- `data/library-cache/` — each component's HTML, CSS, and preview image
- `licenses/` — component licence text

## Licensing

Components belong to their authors and are MIT licensed (see
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)). The viewer and catalog are
covered by [LICENSE](LICENSE). Contributions are not accepted.
