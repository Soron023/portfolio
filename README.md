# Portfolio Website

A modern, responsive portfolio website built with Nuxt 4, TypeScript, and Tailwind CSS.

## Features

- 🎨 Modern UI with Tailwind CSS
- 📱 Fully responsive design
- ⚡ Built with Nuxt 4
- 🔷 TypeScript support
- 🎯 Sections: Home, About, Experience, Projects, Contact
- 🖼️ Profile image integration

## Tech Stack

- **Framework**: Nuxt 4
- **Language**: TypeScript & JavaScript
- **Styling**: Tailwind CSS
- **Frontend**: Vue.js, Nuxt.js

## Getting Started

### Install Dependencies

```bash
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

Visit `http://localhost:3000` to see your portfolio.

### Build

Build for production:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

## Project Structure

```
nuxt-portfolio/
├── app/
│   ├── app.vue          # Root component
│   └── layouts/
│       └── default.vue  # Default layout
├── components/
│   ├── Navigation.vue   # Navigation component
│   └── Footer.vue       # Footer component
├── pages/
│   └── index.vue        # Homepage with all sections
├── assets/
│   └── css/
│       └── main.css     # Tailwind CSS imports
├── public/
│   └── profile.png      # Profile image
└── nuxt.config.ts       # Nuxt configuration
```

## Customization

- Update your profile image by replacing `/public/profile.png`
- Modify the projects in `pages/index.vue`
- Update contact form handling (currently shows alert)
- Customize colors in Tailwind classes throughout components

## Deployment

This portfolio can be deployed to:
- Vercel
- Netlify
- Digital Ocean (as mentioned in your experience)
- Any static hosting service

For Digital Ocean deployment with Nginx, build the project and serve the `.output/public` directory.
