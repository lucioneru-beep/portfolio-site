# Portfolio Site (Vite)

This folder contains a Vite project that serves your existing HTML locally.

Quick start:

```powershell
cd d:\portfolio-site
npm install
npm run dev
```

Open http://localhost:5173 (or the URL printed by Vite).

Build:

```powershell
npm run build
npm run preview
```

## Deploy to Vercel

This project is ready for Vercel. The [vercel.json](vercel.json) file already tells Vercel to use:

- build command: `npm run build`
- output directory: `dist`

### Option 1: Vercel Dashboard (easiest)

1. Push this folder to a GitHub repository.
2. Go to https://vercel.com/new and import that repo.
3. Keep the detected settings (Vite, build: `npm run build`, output: `dist`).
4. Click Deploy.

### Option 2: Vercel CLI

```powershell
cd d:\portfolio-site
npm install
npx vercel login
npx vercel --prod
```

After deploy, Vercel will print your live URL.
