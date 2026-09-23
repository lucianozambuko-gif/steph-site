# Stephanie Osaro — Portfolio

Single-page business portfolio for Stephanie Osaro: program manager, community builder, content strategist and writer based in Abuja.

## Structure

- `index.html` holds the whole site (HTML, CSS and a little JS inline). There's no build step.
- `assets/` holds the optimized photos, event flyers and logo.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
```

## Deploy

The site is static, so it runs on GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder), Netlify or Vercel.

## Contact details

| Detail | Value | Where it appears |
| --- | --- | --- |
| Email | `stephaineosaro@gmail.com` | Contact list, footer, enquiry form (`TO` in the script) |
| Phone / WhatsApp | `+234 816 110 7337` (`2348161107337` in links) | Contact list, footer, "Book a discovery call" |
| Instagram / LinkedIn | `stephanieosaro`: **placeholder, replace with real handles** | Contact list, footer |

## Palette

Burgundy `#4E0F16`, nude/off-white `#EFE6DC`, blush `#EBD6CF` / `#E2C0BD`, rose accent `#8C3341`. All defined as CSS variables at the top of `index.html`.

The enquiry form has no backend: it opens the visitor's email app with the message filled in.
