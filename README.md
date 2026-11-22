# Portfolio Nayla Aguado

Portfolio website for graphic designer and visual artist Nayla Aguado.

Live demo: [portfolio-nayla-one.vercel.app](https://portfolio-nayla-one.vercel.app)

## Tech Stack

- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS
- **Motion & Scrolling:** Framer Motion, Lenis (smooth inertia scrolling), Lucide Icons
- **Tooling:** ESLint, TypeScript

## Key Decisions

- **Inertia Scrolling:** Integrates Lenis to provide consistent smooth scrolling velocity across desktop and mobile devices.
- **Fluid Layouts & Asset Delivery:** Grid and lightbox layouts built with zero layout shifts, loading WebP media dynamically for fast showcase loading.
- **Micro-Interactions:** Custom hover and scroll-triggered animations powered by Framer Motion.

## Local Setup

### Prerequisites

- Node.js 18+

### Installation & Run

```bash
git clone https://github.com/eneekoruiz/portfolio-nayla.git
cd portfolio-nayla
npm install

# Start development server
npm run dev

# Run linter
npm run lint

# Build production bundle
npm run build
```
