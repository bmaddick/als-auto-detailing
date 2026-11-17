# Al's Auto Detailing

Marketing website for Al's Auto Detailing — a premium interior & exterior auto detailing business offering hand washes, paint correction, ceramic coatings, and mobile service.

## Stack

Static site. No build step, no dependencies — just `index.html`, `styles.css`, and `favicon.svg`. Deploys anywhere, optimized for [Vercel](https://vercel.com).

## Develop locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy

```sh
vercel deploy        # preview
vercel deploy --prod # production
```

## Customize before going live

- Replace the placeholder phone (`(555) 123-4567`) and email (`hello@alsautodetailing.com`) in `index.html`.
- Wire the contact form to a real endpoint (Formspree, a serverless function, or a booking tool).
- Swap in real photos and verified review quotes/pricing.
