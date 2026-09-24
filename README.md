# Personal Portfolio — Bilal Ahmad

A five-page personal portfolio website built with plain **HTML5 and CSS3** for
**CS344: Web Engineering — Lab 3 (HTML Advanced: Personal Portfolio II)**.

No JavaScript. No CSS frameworks. All styling lives in a single external
stylesheet, and the layouts are built with the CSS `float` and `clear`
properties as required by the lab.

## Live Site

> GitHub Pages URL: https://Bilal-Ahmad6.github.io/portfolio/

## Pages

| Page | File | Contents |
| --- | --- | --- |
| Home | `index.html` | Hero, quick links to every section, short about |
| Hobbies | `hobbies.html` | Chess, cricket, trekking and food |
| Personal Skills | `skills.html` | Programming languages, spoken languages, other skills |
| Image Gallery | `gallery.html` | 7 real photographs plus their sources |
| Contact Me | `contact.html` | Email, phone, address, GitHub and a message form |

## Project Structure

```
portfolio/
├── index.html          # Home page (entry point for GitHub Pages)
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css       # All styling for every page
├── images/
│   ├── attabad.jpg
│   ├── badshahi.jpg
│   ├── chess.jpg
│   ├── code.jpg
│   ├── hunza.jpg
│   ├── margalla.jpg
│   └── monument.jpg
└── README.md
```

## Lab Requirements Covered

- **External CSS** — every page links `css/style.css`; no inline or internal styles.
- **Float and clear** — images sit beside text, and the gallery uses floated
  figures with `clear` on every third item.
- **Horizontal navigation** — menu items are laid out with `float: left`.
- **Organized folders** — HTML at the root, styles in `css/`, images in `images/`.
- **Version control** — tracked with Git and pushed to GitHub.
- **Deployment** — published with GitHub Pages.

## Design Notes

- Apple-inspired, restrained visual system: a single blue accent (`#0071e3`),
  a system font stack, generous spacing and 20px rounded cards.
- Automatic **dark mode** through `prefers-color-scheme`, so no page ever needs
  an appearance switch.
- Responsive: floated columns collapse to full width on small screens.
- Accessibility: visible keyboard focus rings, alt text on every image and
  tap targets of at least 44px.

## Image Credits

All photographs are openly licensed and sourced from Wikimedia Commons.
Full attribution links appear on the gallery page.

## Author

**Bilal Ahmad** — CMS 501603 — Section SE15A
Faculty of Computing, FAST-NUCES
Course: CS344 Web Engineering, Fall 2026
