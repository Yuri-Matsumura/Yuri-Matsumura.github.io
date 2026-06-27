# Yuri Matsumura — GitHub Pages site

https://yuri-matsumura.github.io/index.html

## File layout

```text
yuri-matsumura.github.io/
├── index.html
├── cv_yuri_matsumura.pdf
├── jmp_00draft.pdf
├── assets/
│   └── css/
│       └── style.css
└── jp/
    └── index.html
```

The English home page is `index.html`. The Japanese page is `jp/index.html`.

## Updating the live site

Upload or commit the files while keeping the two PDF files in the repository root. GitHub Pages will serve `index.html` at the site root.

The site uses EB Garamond for English and Shippori Mincho for Japanese through Google Fonts. The font files are loaded by the browser, so no font files need to be added to this repository.

## Previewing locally

Opening `index.html` directly with `file://` is useful for a quick look, but it is not the same environment as a website. Preview through a local web server for the closest match to GitHub Pages:

```bash
cd path/to/yuri-matsumura.github.io
python3 -m http.server 8000
```

Then open `http://localhost:8000/` in Chrome. On Windows, use `py -m http.server 8000` if `python3` is not available.

## When the live page looks unchanged

After a GitHub upload, reload with `Cmd + Shift + R` on macOS or `Ctrl + Shift + R` on Windows. Also open `https://yuri-matsumura.github.io/assets/css/style.css` directly: it should show the latest stylesheet.
