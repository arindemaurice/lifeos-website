# LIFEOS | Your Life. Connected.

A multi-page website concept for reviewing the direction of LIFEOS before building the real backend.

## Run it
1. Extract the ZIP.
2. Open the `LIFEOS_Multipage_Review` folder in VS Code.
3. Open `index.html` in a browser, or use VS Code's Live Server extension.
4. Explore the navigation. The pages link to each other and selected forms work locally.

## Pages included
- Overview dashboard
- AI Assistant
- Tasks & Plans
- Notes & Ideas
- Calendar
- Money
- Learning & Career
- Creative Studio
- Services & Tools
- Settings & Privacy

## What works in this review build
- Responsive multi-page navigation
- Dark/light theme switch
- Local tasks with completion and deletion
- Local notes with deletion
- Local UGX income/expense entries and totals
- Local events
- Browser-local data export and clear-data control
- Assistant UI that clearly discloses it is not connected to a real AI provider

## Important: this is a UI review build, not production LIFEOS
This ZIP is a front-end review concept. It has **no server, PostgreSQL database, account system, live AI model, web search API, payments, or real external integrations**. The forms save to the current browser's local storage, which is not cloud backup and does not sync between devices. Do not enter sensitive or financial account information.

The next production phase should add:
1. TypeScript component structure and route/layout cleanup.
2. A secure backend API and PostgreSQL database with migrations.
3. Real user authentication, server-side authorization, and account-scoped data.
4. A replaceable AI provider layer, web-search integration, approved memory retrieval, and conversation history.
5. Real provider integrations with status/error handling and explicit confirmation for consequential actions.
6. Automated tests, validation, logging, backups, privacy controls, and deployment configuration.

## Suggested production stack
- Front end: Next.js + TypeScript + Tailwind CSS
- Backend: Next.js server routes or a modular Node.js service
- Database: PostgreSQL + Prisma
- Background jobs/cache: Redis + BullMQ when needed
- AI: server-side provider adapter; API keys never placed in browser code
- Quality: migrations, tests, lint, type checks, build checks, backups, audit logs

LIFEOS is intended to grow continuously through user-approved memories, explicit feedback, evaluation, and controlled updates. That is personalization and product improvement, not automatic retraining of an AI model after every chat.
