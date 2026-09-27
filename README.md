# Booker's

A static, single-page website that showcases a list of popular books, each with a short description. Built with plain HTML and CSS, no frameworks or build step.

![Booker's screenshot](img/Ex/1920px.png)

## Features

- A list of the most popular books, each with a short description
- A sidebar with links that jump to each book's section
- Smooth scrolling between sections (CSS `scroll-behavior: smooth`)
- Google Fonts: **Kaushan Script** for headings, **Noto Sans HK** for body text

## Technologies

- HTML5
- CSS3

## Project structure

```
css_bookers/
├── index.html        # Main page
├── css/
│   └── style.css     # All site styles
├── img/
│   ├── book-png-...png   # Favicon
│   └── Ex/               # Screenshots at 250px, 640px and 1920px widths
└── pages/
    ├── about.html    # Placeholder (empty)
    └── contact.html  # Placeholder (empty)
```

## Getting started

The stylesheet and favicon use root-relative paths (`/css/style.css`), so opening `index.html` directly from disk (`file://`) won't load the styles. Serve the project folder with any static server instead:

```bash
git clone https://github.com/jfbiswajit/css_bookers.git
cd css_bookers

# Python 3
python3 -m http.server 8000
# or Node.js
npx serve .
```

Then open <http://localhost:8000>.

## Known limitations

- **Not responsive.** The layout is designed for desktop screens.
- The book descriptions are placeholder (lorem ipsum) text.
- `pages/about.html` and `pages/contact.html` are empty placeholders.

## Author

Biswajit Biswas ([@jfbiswajit](https://github.com/jfbiswajit))
