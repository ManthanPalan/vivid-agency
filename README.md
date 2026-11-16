# Vivid — Digital marketing agency

A responsive, single-page React website built with Vite. Includes service accordions, a Pinnacle Montessori client feature, agency values, FAQs, mobile navigation, and an embedded CallRail contact form.

## Run locally

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

The build is output to `dist/`.

## Contact form

The contact section uses CallRail form `FOR01a1e4a960bb779fb0d0eaa389a03171` and the existing company swap script. The embed container is present in the initial HTML so CallRail can discover it before React mounts; the component moves that same container into the contact section without recreating it. Contact buttons scroll to the form.

The Pinnacle Montessori logo uses the supplied brand artwork in `public/pinnacle-montessori-logo.jpg`. No performance statistics or testimonials have been invented.
