# Oytun Tükenmez — Academic Website

Personal academic website of Oytun Tükenmez, PhD candidate in Economics at Stockholm University.

**Website:** https://oytuntukenmez.github.io/

The site presents my research, education, teaching, and contact information.

## Maintenance

The site uses standalone [Hugo](https://gohugo.io/) and GitHub Pages. No Hugo Blox theme or Node.js dependencies are required.

- `layouts/index.html` — custom homepage layout
- `static/css/site.css` — website styles
- `assets/media/authors/me.png` — profile photo
- `static/uploads/` — CV
- `hugo.yaml` — Hugo configuration
- `.github/workflows/deploy.yml` — GitHub Pages build and deployment

Changes pushed to `main` trigger automatic deployment. Pull requests are built to check that the site still compiles.
