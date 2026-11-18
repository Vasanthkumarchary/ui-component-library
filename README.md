# UI Component Library

An offline, browsable library of 6,014 community-made HTML + CSS UI components:
buttons, forms, cards, loaders, backgrounds, pop-ups, toggles, and more. Every
preview runs from files in this repository.

## Run it on your computer

You need [Python 3](https://www.python.org/downloads/) installed. Check by
running `python --version` (on macOS or Linux, `python3 --version`).

**1. Get the files.** Either clone the repo with [Git](https://git-scm.com/downloads):

```bash
git clone https://github.com/Vasanthkumarchary/ui-component-library.git
```

or click **Code → Download ZIP** at the top of this page and unzip it.
The download is about 250 MB.

**2. Go into the folder.** Open a terminal (Command Prompt or PowerShell on
Windows, Terminal on macOS or Linux) and move into the folder you just got:

```bash
cd ui-component-library
```

If you downloaded the ZIP, the folder is named `ui-component-library-main`.

**3. Start a local web server** inside that folder:

```bash
python -m http.server 8000
```

On macOS or Linux, use `python3 -m http.server 8000`. Leave this window open
while you use the library.

**4. Open the library** in your browser at
[http://localhost:8000/library/](http://localhost:8000/library/).
Search, browse by group, and open an item to see its live preview and code.
Saved picks stay in your browser.

**5. Stop the server** when you're done: go back to the terminal and press
`Ctrl + C`.

Opening `library/index.html` directly by double-clicking it won't work.
Browsers block it from loading the component files, so it has to run through
the local server in step 3. If port 8000 is already in use, pick another
number, such as `python -m http.server 8080`, and open
`http://localhost:8080/library/` instead.

## Layout

- `library/index.html` — the viewer
- `data/library.json` — catalog (name, author, group)
- `data/library-cache/` — each component's HTML, CSS, and preview image
- `licenses/` — component licence text

## Licensing

Components belong to their authors and are MIT licensed (see
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)). The viewer and catalog are
covered by [LICENSE](LICENSE). Contributions are not accepted.
