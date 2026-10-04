# Eloy Celaya López — Portfolio

Personal portfolio of **Eloy Celaya López**, Data Scientist based in Madrid.

🔗 **Live site:** [www.ecelaya.com](https://www.ecelaya.com)

A single-page, static site built with [Astro](https://astro.build). It covers selected projects, professional experience, education, skills, certifications and contact details, plus a downloadable CV.

## Features

- **Static and fast**: zero client-side framework, plain Astro components and vanilla CSS.
- **Sections**: Hero · Selected Work · Experience · Education · Skills · Certifications · Contact.
- **SEO**: meta and Open Graph tags, JSON-LD `Person` schema, auto-generated sitemap and `robots.txt`.
- **Analytics**: Vercel Analytics and Speed Insights.
- **Responsive** layout built on CSS custom properties.

## Tech stack

| Area      | Tools                                                        |
| --------- | ------------------------------------------------------------ |
| Framework | Astro 7 (TypeScript, strict mode)                            |
| Styling   | Vanilla CSS with custom properties                           |
| Fonts     | DM Sans · Space Grotesk · JetBrains Mono                     |
| SEO       | `@astrojs/sitemap`, JSON-LD                                  |
| Hosting   | Vercel (+ `@vercel/analytics`, `@vercel/speed-insights`)     |

## Project structure

```text
├── public/               # Static assets (CV, certificates, images, favicon, robots.txt)
├── src/
│   ├── components/       # One Astro component per section
│   ├── layouts/
│   │   └── Layout.astro  # <head>, SEO meta, JSON-LD, analytics
│   ├── pages/
│   │   └── index.astro   # Single page that composes all sections
│   └── styles/
│       └── global.css    # Design tokens and global styles
├── astro.config.mjs
└── package.json
```

## Running locally

Requires **Node.js 22.12 or later**.

```bash
npm install
npm run dev        # http://localhost:4321
npm run build      # production build in ./dist
npm run preview    # serve the production build locally
```

## Deployment

The site is deployed on Vercel. Every push to `main` triggers a new production build.

## License

The source code is free to use as a reference or as a starting point for your own portfolio. The personal content (texts, CV, certificates, photos) belongs to Eloy Celaya López and may not be reused.

## Contact

- Email: [eloycl2003@gmail.com](mailto:eloycl2003@gmail.com)
- Web: [www.ecelaya.com](https://www.ecelaya.com)
