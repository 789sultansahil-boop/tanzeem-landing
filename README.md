# تنظیم المدارس اہلسنت پاکستان — landing page

Next.js (App Router) + TypeScript + Tailwind. Urdu-first, RTL.

```bash
npm install
npm run dev     # http://localhost:3000
npm run lint && npm run build
```

Deploy: import the repo in Vercel (framework auto-detected). The site URL for
canonical/sitemap/Open Graph comes from `VERCEL_PROJECT_PRODUCTION_URL`
(set automatically by Vercel). Fonts come from the `@fontsource-variable/*` npm
packages (SIL OFL 1.1). Content lives in `src/lib/content.ts`.
