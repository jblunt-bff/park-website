# Butter Family Farms Website

Official website for **Butter Family Farms (BFF) Amusement Park** in Sandwich, Illinois.

🌐 **Live site:** [butterfamilyfarms.com](https://butterfamilyfarms.com)

## Structure

```
├── index.html        # Home
├── about.html        # About Us
├── visit.html        # Visit Us / rides & attractions
├── merch.html        # Merch shop
├── careers.html      # Job openings
├── news/             # News index + press releases
├── images/           # Logo and article images
└── style.css         # Shared styles
```

## Local development

It's a static site with no build step. Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Adding a news article

1. Copy an existing page in `news/` and rename it using the article slug.
2. Update the title, date, category, and body.
3. Add a card for it at the top of `news/index.html` (newest first).
4. Put any images in `images/news/`.

## Deployment

The site is deployed to the web server behind butterfamilyfarms.com. Copy the repo contents
(excluding `.git`) to the site's web root.
