# Student Finance OS — Technical Roadmap

## Goal
Use AI and open-source software to reduce repetitive work while keeping the business simple and inexpensive.

## Phase 1 — Current
- existing product V1
- Facebook Page
- manual/AI-assisted content creation
- simple landing page when useful
- collect feedback
- validate demand

## Phase 2 — Early automation
### Content engine
- content ideas
- captions
- hooks
- content calendar

### Social publishing
- scheduling
- Facebook Page publishing through appropriate official APIs/tools

### Reel production
- reusable video templates
- programmatic generation where practical

### Landing page
- simple Next.js/static landing page
- low-cost/free hosting initially

### Analytics
- basic content/product metrics

## Phase 3 — Product improvement/build
Use Claude/AI coding tools + GitHub to inspect code, build features, debug, refactor, test, improve UX, and deploy.

Potential future web app:
- authentication
- user dashboard
- money/budget data
- Save First logic
- goals
- review
- payment

## Technical principles
- check open-source licenses before commercial adoption
- never expose secrets/API keys in GitHub
- prefer official APIs for social publishing
- keep components modular
- document setup
- minimize vendor lock-in where practical
- do not over-engineer

## Architecture idea
ChatGPT: business thinking, strategy, product decisions, research, planning.

GitHub: source of truth for code and project documentation.

Claude/AI coding agent: implementation, automation development, debugging, documentation.

Open-source repositories: reusable infrastructure instead of rebuilding every component.

## Current technical decision
Do not start by building the complete business automation platform. Establish the business context first, then choose the smallest useful open-source components and integrate them incrementally.
