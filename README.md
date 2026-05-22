# Rei · AI-Assisted Product Engineering

I build focused software prototypes, internal tools, and product systems with an emphasis on fast execution, clean architecture, and high-autonomy AI-assisted development workflows.

Currently working across three active TypeScript/Next.js product prototypes: a multimedia publication platform, a luxury concierge commerce system, and a mobile QR-scan venue experience.

---

## Current Open Projects

| Project | Product | Current focus | Stack |
|---|---|---|---|
| [Verda](https://github.com/howard86-agents/verda) | Multimedia story and member-engagement platform | CMS/admin flows, reader collections, growth/reward mechanics, local-to-real data migration | Next.js, React, TanStack Query, Dexie, MSW, Prisma, Postgres |
| [Maison](https://github.com/howard86-agents/maison) | Luxury concierge commerce prototype | Sourced products, custom requests, quotes, orders, member accounts, admin/staff data model | Next.js, React, Prisma, Postgres, Better Auth, i18n |
| [Lume](https://github.com/howard86-agents/lume) | QR-scan venue field guide | Mobile scanner experience, 23-specimen collection, localization, on-device progress | Next.js, React, Bun, Turborepo, Prisma, Postgres |

---

## Active Projects

### [Verda](https://github.com/howard86-agents/verda)

A multimedia story and member-engagement platform for a wellness/lifestyle publication concept.

**What it includes**

- Editorial story experience
- Reader collection and growth/reward mechanics
- CMS-style admin pages for articles, media, taxonomy, members, and growth rules
- Local-first browser data path using Dexie behind API/MSW abstractions
- Postgres-backed API migration path for production data
- Image-generation/review pipeline via Bun CLI

**Tech stack**

`TypeScript` · `Next.js` · `React` · `TanStack Query` · `Dexie` · `MSW` · `Prisma` · `PostgreSQL` · `Bun` · `Turborepo` · `Playwright` · `Tailwind CSS`

---

### [Maison](https://github.com/howard86-agents/maison)

A luxury concierge commerce prototype for sourced products, custom requests, quotes, orders, and member accounts.

**What it includes**

- Product collection and concierge shopping flow
- Quote/request lifecycle
- Account, checkout, order, and collection pages
- Admin/staff-oriented data model
- Authentication, roles, i18n, SEO, storage, payments, and notification abstractions
- Bun CLI image pipeline for product/reference assets

**Tech stack**

`TypeScript` · `Next.js` · `React` · `Prisma` · `PostgreSQL` · `Better Auth` · `Bun` · `Turborepo` · `Tailwind CSS` · `Docker Compose`

---

### [Lume](https://github.com/howard86-agents/lume)

A mobile-first QR-scan field guide where venue visitors collect 23 light-form specimens across four floors and unlock a personalized achievement card.

**What it includes**

- QR-code specimen scanning flow
- 23-specimen venue collection mechanic
- Mobile-first visitor experience
- Five-language localized specimen content: `en`, `zh-tw`, `zh-cn`, `ja`, `ko`
- On-device progress persistence so visitors can resume later
- Personalized completion and achievement-card moment

**Tech stack**

`TypeScript` · `Next.js` · `React` · `Bun` · `Turborepo` · `Prisma` · `PostgreSQL` · `Ultracite` · `Biome`

---

## Shared Engineering System

### Frontend

- Next.js App Router
- React
- TypeScript
- Tailwind CSS
- Component-driven UI
- Mobile-first flows where the product needs them
- Locale-aware routing and localized content where needed

### Backend / Data

- Prisma
- PostgreSQL
- API-first data boundaries
- Local-first/browser-side prototypes with Dexie + MSW where useful
- Typed shared data packages
- Clear migration paths from mock/local data to real backend services

### Tooling

- Bun
- Turborepo
- Biome / Ultracite
- Husky git hooks
- Commitlint
- Gitleaks
- Typos
- Dependabot
- GitHub Actions
- Vercel previews

### Testing / Quality

- TypeScript typechecking
- Playwright smoke/e2e tests where useful
- Secret scanning
- Spell checking
- Linting and formatting gates
- Conventional commits
- Small PRs with inspectable diffs

---

## How I Build

I focus on:

- Rapid product prototyping
- Clear data models before UI complexity
- Monorepo structure for reusable packages
- AI-assisted issue execution and review loops
- Spec-first task decomposition
- Small, atomic changes
- Practical quality gates that keep velocity high

---

## Current Focus

- Productized web prototypes
- Agent-assisted software delivery
- Local-first UX patterns
- CMS/admin workflows
- Commerce and concierge systems
- Reward, collection, and engagement mechanics
- Venue/mobile experiences
- QR-scan collection mechanics
- Multilingual on-device experiences

---

## Supporting Infrastructure

### [Workspace Template](https://github.com/howard86-agents/workspace-template)

A reusable Maison-style Bun/Turborepo/Next/Prisma workspace template for bootstrapping Howard agent projects with shared tooling, quality gates, and deployment conventions.
