# ADCO website

Bilingual (Vietnamese / English) redesign of [kientrucadco.vn](https://kientrucadco.vn) for Kiến trúc xây dựng ADCO.

It is a static site: `index.html` plus the images in `assets/`. There is no build step.

## View it locally

```bash
python3 -m http.server 8417
```

Then open http://localhost:8417.

## Hosting

Live at https://adco.homes, hosted on Vercel from this repository: every push to `main` deploys automatically. The domain is registered at Spaceship, with DNS records there pointing to Vercel (`A @ 76.76.21.21`, `CNAME www cname.vercel-dns.com`).

## Before going live

- The contact form opens the visitor's email app addressed to tuvan.kientrucadco@gmail.com. Connect it to a form service so requests are sent directly.
- Confirm the office address: the site says "9 Mỹ Giang 1B, Tân Phong, Quận 7"; recent Facebook posts use "Phú Mỹ Hưng, Tân Hưng".
