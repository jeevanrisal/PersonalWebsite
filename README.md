# Jeevan Portfolio

This is a Next.js 15 portfolio site.

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Host it online (Recommended: Vercel)

### Option 1: Deploy from GitHub (easiest)

1. Create a new GitHub repo and push this project.
2. Go to [https://vercel.com/new](https://vercel.com/new).
3. Import your GitHub repo.
4. If prompted, set these:
   - Framework Preset: `Next.js`
   - Build Command: `npm run build`
   - Output Directory: leave default
5. Click **Deploy**.

Your website will get a live URL like `https://your-site.vercel.app`.

### Option 2: Deploy with CLI

```bash
npm i -g vercel
vercel
vercel --prod
```

## Important note for this machine

Your local environment has another `package-lock.json` higher in the folder tree (`/Users/jeevanrisal/package-lock.json`), so Next.js prints a warning locally.

This does **not** block deployment. To avoid confusion in hosted builds, make sure your deploy root is this folder:

`/Users/jeevanrisal/Documents/Projects/Personal Final`

## Custom domain (optional)

In Vercel:

1. Open your project.
2. Go to **Settings -> Domains**.
3. Add your domain and follow DNS instructions.
