# StudyQuest (Vite + React + Tailwind)

An RPG-style study tracker. 30 min = 10 XP. Level XP = L×50. Streak bonuses and random events.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy
- **Vercel**: Import this repo → Framework: Vite → Build: `npm run build` → Output: `dist/`.
- **Netlify**: New site from Git → Build command: `npm run build` → Publish directory: `dist`.
- **GitHub Pages** (optional): `npm run build` then host `/dist`.

## Env/Monetisation (future)
- Stripe / AdSense hooks can be added in a Pro section.
