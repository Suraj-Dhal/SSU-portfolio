# Dr. Sharanika Dhal — Academic Portfolio

A responsive academic portfolio for **Dr. Sharanika Dhal**, presenting research, publications, books, conference work, science writing, awards, impact, and outreach in one accessible experience.

## Preview

[Visit the live portfolio](https://ssu-portfolio-tau.vercel.app)

## Features

- Dedicated routes for academic content and professional work
- Typed content data that keeps editorial updates separate from presentation code
- Responsive layouts for research, publications, books, conferences, and gallery content
- Motion and chart components for a polished but readable experience
- Static-host deployment support

## Technology

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Framer Motion
- Recharts
- Radix UI primitives

## Project structure

```text
.
├── public/                 # Images, documents, favicon, and other static assets
├── src/
│   ├── components/         # Layout, cards, charts, and reusable UI
│   ├── data/               # Typed portfolio content
│   ├── hooks/              # Reusable React hooks
│   ├── lib/                # Shared helpers
│   ├── pages/portfolio/    # Route-level portfolio pages
│   ├── routes/             # Application route table
│   ├── App.tsx             # Router provider and app shell
│   └── main.tsx            # Vite entry point
├── index.html
└── package.json
```

Keep editorial content in `src/data/`, reusable interface patterns in `src/components/`, and route-specific composition in `src/pages/portfolio/`.

## Getting started

Requirements: Node.js 18.17 or newer and npm.

```bash
npm install
npm run dev
```

Useful checks:

```bash
npm run typecheck
npm run build
```

The production build is written to `dist/`.

## Deployment

Deploy the `dist/` directory to Vercel, Netlify, GitHub Pages, or another static host. The build command is `npm run build`.

## Content updates

Most site copy is centralized in typed files under `src/data/`, including profile, publications, books, awards, gallery, and research content. Update those files rather than duplicating text inside page components.

## Contributing

Preserve accessibility, responsive behavior, and the existing academic tone. Run type-checking and a production build before submitting changes.

## Maintainer

Maintained by [Suraj Dhal](https://surajdhal.com).

## License

No license has been declared yet.
