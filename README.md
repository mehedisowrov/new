https://mehedisowrov.github.io/new/
# Mehedi Hasan's Graphic Design Showcase

A modern, visually striking portfolio website for a freelance graphic designer built with React + TypeScript + Vite.

## Features

- **Hero Section**: Profile photo, name, and professional introduction
- **Services Section**: 6 core offerings with icons (Logo Design, T-Shirt Design, YouTube Thumbnails, etc.)
- **Portfolio Gallery**: Responsive grid layout with lightbox functionality
- **Contact Section**: Simple form with "Hire Me" call-to-action
- **Clean Design**: Black and white color scheme with bold accent colors

## Tech Stack

- React 18 with TypeScript
- Vite for fast development and building
- Tailwind CSS for styling
- ShadCN UI components
- Framer Motion for animations
- React Router for navigation

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## ESLint Configuration

This project uses ESLint with TypeScript and React support. The configuration includes:

- TypeScript type-aware linting
- React and React Hooks rules
- Modern ES2020+ syntax support

To run linting:
```bash
npm run lint
```

## Project Structure

```
src/
├── components/          # React components
│   ├── ui/             # ShadCN UI components
│   ├── HeroSection.tsx
│   ├── ServicesSection.tsx
│   ├── PortfolioGallery.tsx
│   └── ContactSection.tsx
├── lib/                # Utility functions
└── types/              # TypeScript type definitions
```
