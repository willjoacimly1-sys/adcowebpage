# ADCO website

Bilingual (Vietnamese / English) redesign of [kientrucadco.vn](https://kientrucadco.vn) for Kiến trúc xây dựng ADCO.

It is a static site: `index.html` plus the images in `assets/`. There is no build step.

## View it locally

```bash
python3 -m http.server 8417
```

Then open http://localhost:8417.

## Publish it

Upload `index.html` and the `assets/` folder to any static host, for example Netlify (drag the folder onto app.netlify.com/drop), GitHub Pages or Vercel.

## Before going live

- The contact form opens the visitor's email app addressed to tuvan.kientrucadco@gmail.com. Connect it to a form service (for example Netlify Forms) so requests are sent directly.
- The social-share image (`og:image`) still points to the old site. Point it at a file in `assets/` once the new site has its address.
- Confirm the office address: the site says "9 Mỹ Giang 1B, Tân Phong, Quận 7"; recent Facebook posts use "Phú Mỹ Hưng, Tân Hưng".
