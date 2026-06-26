# rswamy.github.io

Personal site and PM portfolio for Ramya Swamy, built with Jekyll and hosted on GitHub Pages.

Live at **[rswamy.github.io](https://rswamy.github.io)**

## Pages

| URL | File | Description |
|-----|------|-------------|
| `/` | `index.md` | Homepage — bio, story, skills |
| `/portfolio/` | `portfolio.html` | PM case studies (SupplyTrust AI tools, 3D Fab Light CAM, IoT platform) |

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Structure

```
_includes/
  head.html       # custom <head> — fonts, SEO, CSS
  header.html     # site nav
  footer.html     # site footer
assets/
  css/style.css   # design system — overrides Minima, shared by all pages
  resume/         # resume PDF
_posts/           # blog posts (not linked from nav)
index.md          # homepage
portfolio.html    # portfolio page (layout: none — self-contained HTML)
```

## Design system

The site uses a custom design layer on top of the [Minima](https://github.com/jekyll/minima) theme:

- **Headings:** DM Serif Display
- **Body:** Inter
- **Monospace:** JetBrains Mono
- **Accent:** `#1d4ed8`
- **Background:** `#fafaf8`

All tokens live in `assets/css/style.css` as CSS custom properties.
