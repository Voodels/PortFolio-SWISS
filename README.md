# Frontend Template — Next.js + Tailwind + Radix

Production-ready App Router starter that mixes the following ingredients:

- Next.js 16 with TypeScript, App Router, and strict linting
- Tailwind CSS v4 with modern gradients and tokens
- Radix UI primitives wired for accessibility (dialog, tabs, tooltip)
- Aceternity UI–style bento grid section with Framer Motion
- Anime.js hero animation showcasing motion patterns

## Prerequisites

- Node.js **>= 20.9.0** (recommended by the Next.js team). Upgrade before running `npm run dev` to avoid runtime errors.
- npm 9+ (ships with current Node LTS).

## Quick Start

```bash
npm install
npm run dev
```

Visit `http://localhost:3000` and explore the three demo sections:

1. **AnimeHero** – motion-powered hero with animated gradients controlled by Anime.js.
2. **RadixShowcase** – tabs, tooltip, and dialog composed from Radix UI primitives.
3. **AceternityGrid** – Aceternity-style bento layout animated with Framer Motion.

## Project Structure

- `src/components/sections/` – reusable sections (hero, radix showcase, aceternity grid).
- `src/lib/utils.ts` – `cn` helper combining `clsx` + `tailwind-merge`.
- `src/app/page.tsx` – stitches the sections into the default landing page.
- `src/app/layout.tsx` – metadata, theme variables, and global gradient background.

## Customisation Tips

- Duplicate any section and tailor the copy, data arrays, or layout.
- Swap or extend Radix primitives by importing additional packages (`@radix-ui/react-*`).
- Add more Aceternity blocks with `npx aceternity-ui add <component>` and place them under `src/components`.
- Adjust motion by editing Anime.js timelines in `anime-hero.tsx` or Framer Motion props in `aceternity-grid.tsx`.

## Scripts

- `npm run dev` – start the Next.js development server.
- `npm run build` – create an optimized production build.
- `npm run start` – serve the production build.
- `npm run lint` – run ESLint across the project.

## Deployment

Deploy with Vercel or any Node-friendly host after running `npm run build`. Ensure the deployment environment uses Node >= 20.9.0.
# PortFolio-SWISS
