# Aegir Co. — Landing Page

Single-page site for Aegir Co. (design, web development and digital solutions).

## Stack

Plain HTML, CSS and JavaScript in a single `index.html`. No build step and no
dependencies; the only external request is the Google Fonts stylesheet.

## Structure

```
index.html      markup, styles and scripts
assets/         logo variants and the underwater artwork
```

## Running locally

Serve the folder over HTTP so the `assets/` paths resolve:

```bash
python -m http.server 8123
```

Then open http://localhost:8123.

## Before publishing

Replace the placeholders in `index.html`:

- WhatsApp number `5500000000000` (2 occurrences)
- E-mail `contato@aegirco.com` (3 occurrences)
- Instagram profile URL
