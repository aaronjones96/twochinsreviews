# Two Chins Reviews

[![Built with Astro](https://astro.badg.es/v2/built-with-astro/small.svg)](https://astro.build)

A food review blog built with Astro, featuring honest restaurant reviews, recipe testing, and culinary adventures.

## 🍕 About

Two Chins Reviews is a food blog dedicated to sharing honest, thoughtful reviews of restaurants, recipes, and culinary experiences. We explore food culture with passion and authenticity.

## 🚀 Quick Start

### Prerequisites

- Node.js 18.14.1 or higher
- npm, pnpm, or yarn

### Installation

1. Clone this repository:
```bash
git clone <your-repo-url> two-chins-reviews
cd two-chins-reviews
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
pnpm run dev
# or
yarn dev
```

4. Open your browser at `http://localhost:4321`

## 📝 Writing Content

### Blog Posts

Create blog posts as Markdown or MDX files in `src/content/blog/`:

```markdown
---
title: "Your Review Title"
date: "2025-01-15"
description: "A brief description"
excerpt: "A short excerpt for listings"
categories: ["Restaurants"] # or ["Recipes"]
tags: ["Pizza", "Italian", "Review"]
---

Your content here...
```

### Categories

Currently supported categories:
- **Restaurants** - Restaurant reviews and dining experiences
- **Recipes** - Recipe testing and cooking adventures

## 🛠️ Commands

| Command | Action |
|---------|--------|
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview your build locally |
| `npm run check` | Check TypeScript types |
| `npm run lint` | Run ESLint |

## ⚙️ Configuration

All site configuration is in `src/config.ts`:

```typescript
export const config = {
  title: "Two Chins Reviews",
  description: "Honest food reviews and culinary adventures",
  author: {
    name: "Two Chins",
    bio: "Food enthusiasts exploring restaurants, recipes, and culinary experiences.",
  },
  siteUrl: "https://yourdomain.com"
};
```

## 🚀 Deployment

This site can be deployed to any static hosting service:

- **Netlify**: Connect your repository and deploy
- **Vercel**: Import your repository and deploy
- **GitHub Pages**: Set up GitHub Actions workflow
- **Cloudflare Pages**: Connect repository and deploy

Make sure to set the `SITE` environment variable to your final deployed URL in your deployment platform's settings.

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.
