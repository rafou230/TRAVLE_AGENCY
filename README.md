# TimeTravel Agency

A fictional luxury travel agency webapp that lets visitors explore three iconic moments in history — Paris 1889, the Cretaceous, and Florence 1504 — and chat with an AI-styled assistant for recommendations and booking info.

## Technologies

- React 18 (via CDN, no build step)
- Tailwind CSS (via CDN)
- Babel Standalone (in-browser JSX compilation)
- Vanilla JS chatbot logic (predefined Q&A matching)

## Features

- Landing page with hero section
- About / agency presentation section
- Three destination "boarding pass" cards (Paris 1889, Cretaceous, Florence 1504)
- Floating AI chatbot ("TimeTravel Assistant") with predefined answers on destinations, pricing, recommendations, and booking
- Fully responsive (mobile-first)
- Keyboard-accessible focus states, reduced-motion support

## AI tools used

- Claude (Anthropic) — full design, copywriting, and code generation

## Project structure

```
timetravel-agency/
├── index.html   (entire app: markup, styles, React components, chatbot logic)
└── README.md
```

Everything lives in a single `index.html` file on purpose — no `npm install`, no build step. Open it directly in a browser, or deploy it as-is.

## Deployment

**Netlify (drag & drop, no account needed to preview):**
1. Go to https://app.netlify.com/drop
2. Drag the `timetravel-agency` folder onto the page
3. Netlify gives you a live public URL in seconds

**Vercel (if you prefer):**
1. Create a new GitHub repo and push this folder
2. Import the repo on https://vercel.com/new
3. No build command needed — set the output directory to `/` (static site)

## License

Educational project.
