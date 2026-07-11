# windpixi-site 💖

Personal site with a Y2K bubblegum aesthetic — link-in-bio home page,
photo portfolio, and a support/fund page.

Static HTML/CSS, no build step. Deployable anywhere (GitHub Pages, Netlify, etc.).

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Link page — all socials in one place |
| Portfolio | `portfolio.html` | Photo album grid |
| Fund | `fund.html` | Wishlist, tips & newsletter |

## Editing

Everything you need to personalize is marked with `EDIT ME` comments:

- **Social links** — `index.html`, swap each `href="#"` in the link list
- **Photos** — replace `assets/placeholder-N.svg` with your images and
  update the captions in `portfolio.html`
- **Wishlist / tip links** — `fund.html` (`My Wishlist` button + tip row)
- **Newsletter form** — `fund.html`; point the form `action` at your mailing
  list provider (Mailchimp / Buttondown / beehiiv give you a form URL)

Shared styles (colors, fonts, components) live in `css/style.css` — the
palette is defined as CSS variables at the top.

## Run locally

```sh
python3 -m http.server 4173
# → http://localhost:4173
```
