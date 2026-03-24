# CLAUDE.md — Clean Shopper

## Project Overview

Clean Shopper is an AI-powered product research assistant that helps users find clean, non-toxic home and personal care products.

## Project Structure

- `src/components/` — Reusable UI components
- `src/hooks/` — Custom React hooks
- `src/lib/` — Utilities, API clients, and helper functions
- `src/pages/` — Page-level components and routing
- `src/styles/` — Global CSS styles
- `docs/` — Project documentation and briefs

## Development

```bash
npm install    # Install dependencies
npm start      # Start development server (http://localhost:3000)
npm run build  # Production build
npm test       # Run tests
```

## Notes for Claude

- Keep components small and focused on a single responsibility.
- Place API/fetch logic in `src/lib/`.
- Place reusable stateful logic in `src/hooks/`.
- See `docs/CCDCourse_CleanShopper_ProjectBrief.md` for full product requirements.
