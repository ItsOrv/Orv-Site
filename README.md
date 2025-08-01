# Orv Portfolio Website

A modern, interactive portfolio website built with React, TypeScript, and advanced web technologies. Features a terminal-inspired design with smooth animations and professional styling.

## Features

- Terminal-Inspired Design: Modern terminal aesthetic with typing animations
- Smooth Animations: Powered by Framer Motion and GSAP
- Responsive Design: Fully responsive across all devices
- Interactive Elements: Terminal playground, typing sounds, background music
- Professional Sections: About, Skills, Projects, Contact sections
- Customizable Content: All content managed through `src/content.ts`

## Tech Stack

- Frontend: React 18, TypeScript
- Build Tool: Vite
- Styling: Tailwind CSS
- Animations: Framer Motion, GSAP, ScrollTrigger
- Smooth Scrolling: Lenis
- Audio: Custom typing sounds and background music

## Project Structure

```
src/
├── components/          # React components
│   ├── AboutSection.tsx
│   ├── SkillsSection.tsx
│   ├── ProjectsSection.tsx
│   ├── ContactSection.tsx
│   ├── BootScreen.tsx
│   ├── HeroTerminal.tsx
│   ├── BackgroundMusic.tsx
│   ├── TerminalPlayground.tsx
│   └── ...
├── content.ts          # All customizable content
├── App.tsx            # Main application component
├── main.tsx           # React entry point
└── index.css          # Global styles and Tailwind
```

## Design Features

- Glass Morphism: Modern glass effects and blur
- Gradient Backgrounds: Dynamic animated gradients
- Terminal Headers: macOS-style terminal windows
- Progress Bars: Animated skill progress indicators
- Hover Effects: Smooth hover animations
- Particle System: Floating animated particles

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ItsOrv/Orv-Site.git
cd Orv-Site
```

2. Install dependencies:
```bash
npm install
```

3. Start development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

### Build for Production

```bash
npm run build
```

## Deployment

### Netlify (Recommended)

1. Build the project:
```bash
npm run build
```

2. Deploy to Netlify:
   - Connect your GitHub repository to Netlify
   - Set build command: `npm run build`
   - Set publish directory: `dist`
   - Deploy automatically on push to main branch

### Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

### GitHub Pages

1. Add to package.json:
```json
{
  "homepage": "https://yourusername.github.io/repository-name",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  }
}
```

2. Install gh-pages:
```bash
npm install --save-dev gh-pages
```

3. Deploy:
```bash
npm run deploy
```

### Manual Deployment

1. Build the project:
```bash
npm run build
```

2. Upload the `dist` folder to your web server

3. Configure your server to serve `index.html` for all routes (SPA routing)

## Customization

All content is centralized in `src/content.ts`. You can easily modify:

- Profile information
- Skills and expertise levels
- Project details
- Contact information
- Section headings and descriptions

## Sections

- Hero: Animated terminal with typing effect
- About: Professional background and focus areas
- Skills: Interactive skill bars with progress
- Projects: Featured projects with tech stack
- Contact: Contact information and social links

## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Key Components

- App.tsx: Main application with routing and animations
- content.ts: Centralized content management
- index.css: Global styles and Tailwind configuration

## Responsive Design

The website is fully responsive and optimized for:
- Desktop (1920px+)
- Laptop (1366px)
- Tablet (768px)
- Mobile (375px)

## Audio Features

- Typing sound effects
- Background music player
- Audio controls and mute functionality

## Performance

- Optimized animations with GSAP
- Smooth scrolling with Lenis
- Efficient React rendering
- Minimal bundle size

---

Built with React, TypeScript, and modern web technologies.
