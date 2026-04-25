# lottemertens.com

Personal academic CV website, hosted on GitHub Pages at [lottemertens.com](https://lottemertens.com).

## Structure

```
index.html          — Homepage
CV.html             — Curriculum vitae
Articles.html       — Publications and articles
Conferences.html    — Conference presentations
AG.html             — Additional page
CV.pdf              — Downloadable CV
Kidsweek.pdf        — Kidsweek article
Presentation.jpeg   — Presentation image
css/                — Stylesheets (Bootstrap, Font Awesome, main.css, site.css)
images/             — Photos and images
scripts/            — JavaScript (Bootstrap, AOS animations, main.js)
favicon.ico         — Site icon
```

## Editing

Open any `.html` file in a text editor (e.g. VSCode), make your changes, and push to GitHub. The site updates automatically within a minute.

```bash
git add .
git commit -m "describe your change"
git push
```

## Hosting

Served by GitHub Pages from the `main` branch. Custom domain configured via DNS at mijndomein.nl:
- `lottemertens.com` → GitHub Pages (A records)
- `www.lottemertens.com` → GitHub Pages (CNAME)
