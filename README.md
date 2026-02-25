# Akshat Portfolio

Personal portfolio website built with React, TypeScript, Vite, GSAP, and Three.js.

## Tech Stack

- React 18
- TypeScript
- Vite
- GSAP
- Three.js / React Three Fiber

## Prerequisites

- Node.js 18+ (recommended: latest LTS)
- npm 9+

## Installation

1. Clone the repository

```bash
git clone <your-repo-url>
cd akshat
```

2. Install dependencies

```bash
npm install
```

3. Configure environment variables

```bash
cp .env.example .env
```

Then open `.env` and set your real key:

```env
GROQ_API_KEY=your_actual_groq_api_key
```

## Run Locally

Start development server:

```bash
npm run dev
```

Default local URL:

```text
http://localhost:5173
```

## Build for Production

```bash
npm run build
```

Preview production build locally:

```bash
npm run preview
```

## Notes

- Keep `.env` private (already ignored by `.gitignore`).
- If your API key was ever exposed, rotate it in your Groq dashboard.

## License

This project is open source and available under the [MIT License](LICENSE).
