# Dr. Sharanika Dhal — Academic Portfolio

Personal academic portfolio website for **Dr. Sharanika Dhal**, presenting her research, publications, books, conference work, science writing, awards and outreach in one place.

Built with **React + TypeScript + Vite**, styled with **Tailwind CSS**, animated with **Framer Motion**, with charts from **Recharts**.

## Pages

| Page | Route |
| --- | --- |
| Home | `/` |
| About | `/about` |
| Experience | `/experience` |
| Research Themes | `/research-themes` |
| Publications | `/publications` |
| Books | `/books` |
| Conferences | `/conferences` |
| Science Writing | `/science-writing` |
| Impact | `/impact` |
| Awards | `/awards` |
| Gallery | `/gallery` |
| Contact | `/contact` |

Routes are defined in [`src/routes/router.tsx`](src/routes/router.tsx).

## Project structure

```
.
├── index.html            # Vite entry
├── public/               # Static files (images, resume.pdf, favicon)
└── src/
    ├── main.tsx          # App bootstrap
    ├── App.tsx           # Router provider
    ├── routes/           # Route table
    ├── pages/portfolio/  # One file per page
    ├── components/       # Layout, cards, charts and UI primitives
    ├── data/             # All site content (edit these to update the site)
    ├── hooks/            # Reusable React hooks
    └── lib/              # Helpers
```

## Updating content

All text lives in typed data files under [`src/data/`](src/data) — for example `profile.ts`, `publications.ts`, `books.ts`, `awards.ts`, `gallery.ts`. Edit a file, commit, and the site rebuilds. Images go in `public/images/`.

## Run locally

Requires Node.js 18.17 or newer.

```bash
npm install
npm run dev        # start dev server
npm run build      # type-check + production build to dist/
npm run typecheck  # type-check only
```

## Deploy

Any static host works (Vercel, Netlify, GitHub Pages). Build command `npm run build`, output directory `dist`.

---

Maintained by [Suraj Dhal](https://surajdhal.com).
