# Portfolio Website

Personal portfolio website built with **Astro** and **Tailwind CSS**, designed to be fast, minimal, and content-focused.

The site follows a guided, non-scrolling layout on desktop, with responsive scrolling on mobile, and highlights selected work, skills, and contact information.

## Tech Stack

- Astro – static-first framework for maximum performance
- Tailwind CSS – utility-first styling
- TypeScript – type safety and maintainability
- Static output – deployable to Cloudflare Pages, Vercel, or GitHub Pages

## Features

- Ultra-fast static pages
- Responsive design (mobile scroll, desktop fixed layout)
- Guided navigation (Back / Next + keyboard arrows)
- Centered layout optimized for large screens
- Frosted header and footer for better readability while scrolling
- Minimal JavaScript (only for keyboard navigation)
- Clean, senior-focused content structure

## Project Structure

src/
  layouts/
    FlowLayout.astro
  pages/
    index.astro
    about.astro
    work.astro
    skills.astro
    contact.astro
  styles/
    global.css
public/
  resume.pdf

## Development

Install dependencies and run locally:

npm install
npm run dev

The site will be available at:
http://localhost:4321

## Build

Generate a production build:

npm run build

Output is generated in the dist/ directory.

## Deployment

This project is fully static and can be deployed to:

- Cloudflare Pages (recommended)
- Vercel
- GitHub Pages

Typical Cloudflare Pages settings:
- Build command: npm run build
- Output directory: dist

## Customization

- Update page content inside src/pages
- Replace public/resume.pdf with your own resume
- Adjust layout and navigation in src/layouts/FlowLayout.astro

## License

This project is for personal use. Feel free to use it as inspiration, but please do not copy the content directly.
