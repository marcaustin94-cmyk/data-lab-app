# Data Lab App

A phone-first React/Vite PWA prototype.

## Deploy on Vercel

1. Create a new GitHub repository.
2. Upload these files/folders to the repository root:
   - `src`
   - `public`
   - `index.html`
   - `package.json`
   - `vite.config.js`
   - `vercel.json`
3. In Vercel, choose **Add New > Project**.
4. Import the GitHub repo.
5. Vercel should auto-detect Vite. If not, use:
   - Framework preset: Vite
   - Build command: `npm run build`
   - Output directory: `dist`
   - Install command: `npm install`
6. Deploy.

## Run locally

```bash
npm install
npm run dev
```
