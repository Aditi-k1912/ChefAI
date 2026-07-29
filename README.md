# ChefAI

AI-powered social commerce platform for home food businesses.

## Tech Stack

- **Framework:** Next.js 15 (App Router) + React 18 + TypeScript
- **Styling:** Tailwind CSS v4 + shadcn/ui + Framer Motion
- **Database:** PostgreSQL via Supabase, accessed through Prisma ORM
- **Auth:** Clerk
- **Storage:** Supabase Storage
- **Payments:** Razorpay
- **Charts:** Recharts
- **AI:** OpenAI API (behind a swappable provider interface)
- **Deployment:** Vercel

## Getting Started

### 1. Prerequisites

- Node.js 20+
- npm 10+

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

```bash
cp .env.example .env.local
```

Fill in the values as each service is configured (Supabase, Clerk, Razorpay,
OpenAI — added incrementally in later build steps). `NEXT_PUBLIC_APP_URL` is
the only variable required to run the app right now.

### 4. Run the dev server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

### 5. Other scripts

```bash
npm run build          # production build
npm run start           # run the production build
npm run lint             # ESLint
npm run format           # Prettier — write
npm run format:check     # Prettier — check only
npm run type-check       # TypeScript, no emit
```

## Project Status

This project is being built incrementally. Current step: **1 — Project
Initialization**.
