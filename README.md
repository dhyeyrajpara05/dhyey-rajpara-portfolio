# Dhyey Rajpara — Portfolio

A polished, responsive portfolio for a Cyber Security student and developer. The visual language pairs deep navy surfaces with restrained blue and purple accents, technical labels, and subtle motion.

## Features

- Responsive navigation and command-center inspired hero
- Animated role text and profile statistics
- About, security practice, skills, selected projects, experience, education, certifications, cyber journey and contact sections
- Project category filters and accessible detail dialogs
- Reduced motion support, visible keyboard focus and semantic landmarks
- Editable portfolio content in `src/data/portfolio.ts`
- GitHub Pages workflow for the `main` branch

## Tech stack

React, TypeScript, Vite, Tailwind CSS, custom responsive CSS, Framer Motion and Lucide React.

## Getting started

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deployment

1. Push this repository to GitHub as `dhyey-rajpara-portfolio`.
2. In repository Settings → Pages, set the source to **GitHub Actions**.
3. Push to `main` or run the **Deploy to GitHub Pages** workflow manually.

Vite uses `/dhyey-rajpara-portfolio/` as its base in GitHub Actions builds and `/` for local development. If you choose a different repository name, update `base` in `vite.config.ts`.

## Project structure

```text
src/
  App.tsx                 Main page and reusable section components
  index.css               Responsive theme and component styling
  main.tsx                React entry point
  data/portfolio.ts       Projects, skills, profile stats and social URLs
public/
  favicon.svg
.github/workflows/
  deploy.yml
```

## Personalize before publishing

Update profile values, project descriptions and links in `src/data/portfolio.ts`. Replace sample repository, organization, university, credential and contact information with verified details. The contact form is frontend-only; connect Formspree or EmailJS in `Contact` before relying on message delivery.
