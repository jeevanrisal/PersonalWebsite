# Jeevan Risal Portfolio

Modern personal portfolio built with Next.js 15, React 19, and Tailwind CSS.
It includes sections for projects, experience, education, and contact details with a polished interactive UI.

## Tech stack

- Next.js 15 (App Router)
- React 19
- Tailwind CSS 3
- Geist font
- Lucide icons

## Features

- Single-page portfolio flow: Hero, Strengths, Projects, Experience, Education, Contact
- Data-driven content from one central file (`data/siteData.js`)
- Smooth UI details (pointer effects, magnetic interactions, section transitions)
- Responsive layout for desktop and mobile
- Production-ready static build output

## Project structure

```text
app/
  layout.jsx
  page.jsx
  globals.css
components/
  Hero.jsx
  Projects.jsx
  Experience.jsx
  Education.jsx
  Contact.jsx
  ...
data/
  siteData.js
hooks/
  useMagnetic.js
```

## Getting started

### 1) Install dependencies

```bash
npm install
```

### 2) Start local development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Available scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run start` - Run production server locally
- `npm run lint` - Run ESLint checks

## Customize content

Most portfolio content can be updated in:

- `data/siteData.js` - social links, projects, experience, education
- `app/layout.jsx` - page metadata (title + description)
- `app/globals.css` - theme, effects, and global styling

## Deployment (Vercel)

### Option A: Deploy from GitHub

1. Push this repository to GitHub.
2. Open [Vercel New Project](https://vercel.com/new).
3. Import the repository.
4. Confirm:
   - Framework Preset: `Next.js`
   - Build Command: `npm run build`
5. Deploy.

### Option B: Deploy with Vercel CLI

```bash
npm i -g vercel
vercel
vercel --prod
```

## Notes

- If Next.js warns about multiple lockfiles on your machine, it is usually due to another `package-lock.json` outside this project directory.
- For hosting, always set the project root to this folder:
  `/Users/jeevanrisal/Documents/Projects/Personal Final`

## License

Personal project. Update license terms as needed before public redistribution.
