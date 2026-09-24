# Wanale CT Campsite

A responsive campsite website using the supplied photography, with package rates, gallery filters, keyboard-accessible photo lightbox, video, subtle perspective effects and WhatsApp booking enquiries.

## Run

```sh
npm install
npm run dev
```

## Production

```sh
npm run build
npm run preview
```

Deploy this folder on Vercel with the Vite preset. The build command is `npm run build` and output directory is `dist`; `vercel.json` supplies these settings. No environment variables or backend are required. Only the production output is served, not the original reference images or WhatsApp screenshots in `pics`.

## Content

- Edit page copy and package prices in `index.html`.
- Edit gallery entries and WhatsApp message formatting in `app.js`.
- Published photos are optimized WebP files in `public/assets`.
- WhatsApp destination: `256702267620`.
- The form opens a prepared enquiry, without sending it automatically or confirming a reservation.
- Rates come from the owner's supplied messages. Package duration and club-discount applicability are confirmed by the campsite team. No founding dates or unverified historical claims have been added.
- The image depth treatment uses CSS perspective, layered crops, hover tilt and scroll reveals; these are not reconstructed 3D models. Reduced-motion preferences are respected.

## Validation

Production build and JavaScript syntax checks passed. Browser checks covered rate switching, gallery filtering, lightbox opening/closing, image loading, and a 390px mobile viewport without horizontal page overflow.
