# Payload CMS + Next.js Sandbox

A local working copy of the [Payload CMS](https://payloadcms.com) Next.js starter that I use to explore **headless CMS** APIs, the admin UI and TypeScript content modelling.

> This repository is based on the official Payload CMS template. Upstream credits and license remain in `LICENSE.md`.

## What's here

- Payload admin panel under `src/app/(payload)/admin`
- REST and GraphQL API routes under `src/app/(payload)/api`
- Content config in `payload.config.ts` with generated types in `payload-types.ts`
- Local SQLite database file `payload.db`
- Upstream contributing, security and issue guides

## Run locally

```bash
pnpm install
cp .env.example .env
pnpm dev
```

Then open the admin panel at `http://localhost:3000/admin`.

## Author

**Rumesh** â€” Full-Stack & AI Engineer, Timisoara, Romania.  
GitHub: https://github.com/rumeshprasanga66-boop  
Email: rumeshprasanga66@gmail.com