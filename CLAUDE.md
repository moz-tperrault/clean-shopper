<<<<<<< HEAD
# Clean Shopper — Claude Code Instructions

## Project
Clean Shopper is a personal product research assistant for ingredient-aware consumers. Users search for home and personal care products, get AI-generated clean/not-clean assessments based on ingredient safety data, save products to a personal library organized by category, and build shopping lists.

Single-user app. No authentication in V1. Local state plus Supabase for data persistence.

## Tech Stack
- React (Vite) -- frontend UI
- Supabase -- database and data layer (PostgreSQL)
- Claude API (claude-sonnet-4-20250514) -- AI product research and ingredient analysis
- EWG Skin Deep API -- ingredient safety data
- Vercel -- deployment
- Tailwind CSS -- styling

## Conventions
- Components: PascalCase filenames, one component per file, lives in /src/components/
- Utility functions: camelCase, lives in /src/lib/
- API calls: all external API calls through /src/lib/api/, never inline in components
- Styling: Tailwind only. No inline styles. No CSS modules.
- State: React useState and useContext only. No Redux, no Zustand.
- File naming: kebab-case for all non-component files

## Do Not
- Do not add user authentication or account features -- V1 is single-user only
- Do not use CSS other than Tailwind
- Do not add features outside the current build phase without asking first
- Do not create new components when an existing component in the component library covers the use case
- Do not use any AI model other than claude-sonnet-4-20250514

## References
- Component library: See /docs/component-spec.md -- use existing components before creating new ones
- Build plan: See /docs/build-plan.md -- build phase by phase, do not jump ahead
- Project context: See /docs/project-context.md -- full project intake and design decisions
- Project context skill: See /.claude/skills/project-context/SKILL.md -- use /project-context to generate a structured context document from any project input
=======
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
>>>>>>> 74a0890915fba73a785b6d0035e24a7b2c6c82a9
