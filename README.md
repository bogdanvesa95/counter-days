# counter-days-ts-shadcn-framer

Vite + React + TypeScript + Tailwind + Framer Motion - Mobile-first countdown app pentru "Marea Ciubăreală".

## Schimbă data țintă
Editează `src/App.tsx` și modifică `const targetDate = new Date("2025-09-20T00:00:00")` la data dorită.

## Rulare local
```bash
npm install
npm run dev
```
Deschide `http://localhost:5173`.

## Deploy pe GitHub Pages
1. Creează un repo public numit `counter-days-ts-shadcn-framer`.
2. În `package.json` înlocuiește `"homepage"` cu `https://<USERNAME>.github.io/counter-days-ts-shadcn-framer`.
3. Commit & push.
4. Rulează:
```bash
npm run deploy
```
