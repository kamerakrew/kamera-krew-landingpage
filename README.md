# Kamera Krew — Landing Page

Premium wedding photography & films website for **Kamera Krew**, based in Nagpur and available worldwide.

🌐 Live site: [kamerakrew.com](https://kamerakrew.com)

## About

A static HTML/CSS/JS website served via GitHub Pages with a custom domain (`CNAME` → `kamerakrew.com`).

## Structure

| Page | Purpose |
| --- | --- |
| `index.html` | Home / landing page |
| `portfolio.html` | Portfolio overview |
| `portfolio-*.html` | Category galleries (wedding, prewedding, engagement, haldi, mehendi, reception, baby shoot, destination, events) |
| `films.html` | Films / videography |
| `stories.html` | Client stories |
| `contact.html` | Contact page |
| `links.html` | Link hub |
| `assets/` | CSS, JS, and other static assets |
| `images/` | Site imagery and gallery photos |

## Local preview

The site is fully static — open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

Pushing to the `main` branch publishes automatically via GitHub Pages. The custom domain is configured through the `CNAME` file.
