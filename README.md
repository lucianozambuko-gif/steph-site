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

## Placeholder contact details — replace before real use

The contact section uses generic details for the client preview. Find and replace them throughout `index.html`:

| Placeholder | Where it appears |
| --- | --- |
| `hello@stephanieosaro.com` | Contact list, footer, enquiry form (`TO` in the script) |
| `2348000000000` / `+234 800 000 0000` | WhatsApp links and phone number |
| `stephanieosaro` | Instagram and LinkedIn links |

The enquiry form has no backend: it opens the visitor's email app with the message filled in.
