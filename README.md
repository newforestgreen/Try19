# Portfolio site (static)

Dit is een framework-loze, statische site (alleen HTML/CSS/JS). Alles draait lokaal en kan zo naar Netlify/Vercel/GitHub Pages.

## Aanpassen (meest belangrijk)

1) **Projecten**
- `data/projects.js` — portfolio projecten
- `data/ongoing.js` — doorlopende projecten

2) **Beelden**
- Vervang de placeholders `images/project-0X.svg` door echte foto’s.
- Tip: gebruik consistente bestandsnamen, bv. `images/magic-circle-01.jpg`.

3) **Contact**
- `about.html` — vervang `hello@example.com` en socials.

## Structuur

- `index.html` — landing
- `portfolio.html` — portfolio + filters
- `project.html` — project detail
- `ongoing.html` — ongoing + filters
- `ongoing-project.html` — ongoing detail
- `about.html` — missie/werkwijze/contact
- `styles.css` — gedeelde styling

## Lokaal openen

Dubbelklik kan werken, maar sommige browsers blokkeren `file://` scripts.
Gebruik liever een simpele lokale server:

- Python: `python -m http.server 8000`
- Node: `npx serve`

Open daarna `http://localhost:8000`.
