# Hurrian Network Website

Astro-based template website for Hurrian Network.

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or pnpm

### Installation
```bash
npm install
```

### Development
```bash
npm run dev
```

### Build
```bash
npm run build
```

### Preview
```bash
npm run preview
```

## Deployment

This project is configured for deployment on Railway. Connect your GitHub repository to Railway and it will automatically deploy.

## Project Structure

```
/
├── src/
│   ├── components/
│   │   ├── FAQ.astro
│   │   └── Reviews.astro
│   ├── content/
│   │   ├── blog/
│   │   │   └── *.md
│   │   └── config.ts
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── blog/
│       │   ├── [...slug].astro
│       │   └── index.astro
│       ├── career.astro
│       └── index.astro
├── astro.config.mjs
├── package.json
├── railway.json
└── tsconfig.json
```

## Configuration

Edit `src/pages/index.astro` to customize the site content:
- Reference URL
- Hero section text
- Features
- CTA links

## Reference URL
Reference URL for this site: https://technetwork.com/ref/hurrian
