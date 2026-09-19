# vinayaknageli.in

Personal site for Vinayak N. — Senior Scientist, Center for AI and Robotics
(CAIR), Bangalore. Six pages: Home, About, Research, Publications,
Art & Spirituality, Contact.

Plain HTML/CSS/JS, hosted on GitHub Pages with a custom domain
(`vinayaknageli.in`) pointed here via GoDaddy DNS.

Drop the hero background photo at `assets/img/hero-bg.jpg` — the home page
hero references it directly (falls back to a plain gradient if absent).

## Local preview

Open `index.html` directly in a browser, or serve it:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deployment

Pushing to the `main` branch and enabling GitHub Pages (Settings → Pages →
Deploy from branch → `main` / `root`) publishes the site automatically. The
`CNAME` file points it at `vinayaknageli.in`.
