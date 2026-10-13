# jacobschireson.com

Personal site, built with [Eleventy](https://www.11ty.dev/) and deployed to GitHub Pages on every push to `main`.

## Editing

```sh
npm install   # first time only
npm start     # live preview at http://localhost:8080
```

| To change…               | Edit                         |
| ------------------------ | ---------------------------- |
| Resume                   | `src/resume.html`            |
| Projects                 | `src/_data/projects.json`    |
| Contact page             | `src/contact.html`           |
| Nav links                | `src/_data/nav.json`         |
| Shared page shell / menu | `src/_includes/layout.njk`   |
| Styles                   | `src/css/style.css`          |

Then commit and push; the site updates in about a minute.
