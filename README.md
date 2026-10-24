# BT Rental — Forklift Rental Landing Page

A Spanish-language landing page prototype for a forklift rental business, built with HTML, CSS and vanilla JavaScript.

The page presents services, a rental workflow, an equipment gallery and frequently asked questions, with WhatsApp links for quote requests.

## Highlights

- Responsive layout with prominent calls to action.
- WhatsApp quote links with prefilled messages.
- Image gallery with lazy loading and responsive hero imagery.
- FAQ section and business contact information.
- Search and social sharing metadata.
- Single-page structure without a build step or framework.

## Preview locally

Requires Python 3 for a static preview server:

```sh
git clone https://github.com/Hanyer001/Pagina-de-prueba.git
cd Pagina-de-prueba
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/). On Windows, use `py` instead of `python3` if needed.

## Files

```text
index.html           Page content, styles and interactions
img/logo.jpg         Logo asset
img/logo-banner.jpg  Banner asset
```

External photos load from Unsplash and require an internet connection.

## Project status

This is a frontend prototype. The source explicitly includes sample business figures, copy and photography; they should be verified and replaced before a commercial launch. The quote buttons open WhatsApp rather than submitting to a backend. Avoid sending test inquiries to the business contact.

For a release, review the copy, contact destination, image rights, download size, mobile layout and social preview image URL. This repository does not include automated tests or a backend service.
