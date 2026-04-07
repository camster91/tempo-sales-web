# Tempo Sales Web

A modern sales and marketing website built with Next.js 16, React 19, and Tailwind CSS 4.

## Project Overview

Tempo Sales Web is a high-performance marketing website designed for rapid content delivery and optimal user engagement. Built with the latest Next.js features, it provides a solid foundation for sales-focused web experiences.

## Tech Stack

### Frontend
- **Next.js 16.2.2** - Latest Next.js with App Router
- **React 19.2.4** - Latest React with improved concurrent features
- **TypeScript 5** - Type-safe development
- **Tailwind CSS 4** - Latest Tailwind with improved performance

### Development Tools
- **ESLint 9** - Code linting
- **PostCSS** - CSS processing

## Key Features

- **App Router** - Modern Next.js routing with layouts and streaming
- **Server Components** - Optimized rendering with React Server Components
- **Tailwind CSS 4** - Utility-first styling with improved DX
- **TypeScript** - Full type safety across the codebase
- **Geist Font** - Modern typography from Vercel

## Installation

### Prerequisites
- Node.js v18+ (v20+ recommended)
- npm, yarn, pnpm, or bun

### Setup

```bash
# Clone the repository
git clone https://github.com/camster91/tempo-sales-web.git
cd tempo-sales-web

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the site.

## Usage

### Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linting
npm run lint
```

### Project Structure

```
src/
├── app/           # Next.js App Router pages
│   ├── layout.tsx # Root layout
│   └── page.tsx   # Home page
└── public/        # Static assets
```

### Customization

1. Edit `src/app/page.tsx` to modify the home page
2. Update `src/app/layout.tsx` for site-wide layout changes
3. Add pages by creating new directories in `src/app/`

## Deployment

### Vercel (Recommended)

The easiest deployment method:

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Docker

```bash
# Build
docker build -t tempo-sales-web .

# Run
docker run -p 3000:3000 tempo-sales-web
```

### Static Export

```bash
# Configure next.config.ts for static export
npm run build
# Output in ./out directory
```

## Environment Variables

Create a `.env.local` file for environment-specific configuration:

```env
# Example variables
NEXT_PUBLIC_SITE_URL=https://your-domain.com
NEXT_PUBLIC_ANALYTICS_ID=your-analytics-id
```

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint |

## Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Learn Next.js](https://nextjs.org/learn)

## License

Developed by Cameron Ashley / Nexus AI
