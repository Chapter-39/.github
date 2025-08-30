# Chapter 39

🚀 **Chapter 39** is a set of templates and utilities to accelerate app development.
The goal is to keep a common, modular foundation so we don't reinvent the wheel on every project.

---

## 🔹 Main repositories

- **.github** → [github.com/Chapter-39/.github](https://github.com/Chapter-39/.github) (🪿 Public repo)
- **app-template** → [github.com/Chapter-39/app-template](https://github.com/Chapter-39/app-template) (🦆 Public template)
- **backend-template** → [github.com/Chapter-39/backend-template](https://github.com/Chapter-39/backend-template) (🦆 Public template)
- **design-template** → [github.com/Chapter-39/design-template](https://github.com/Chapter-39/design-template) (🦆 Public template)
- **docs** → [github.com/Chapter-39/docs](https://github.com/Chapter-39/docs) (🦉 Private repo)
- **landing-template** → [github.com/Chapter-39/landing-template](https://github.com/Chapter-39/landing-template) (🦆 Public template)
- **minimal-template** → [github.com/Chapter-39/minimal-template](https://github.com/Chapter-39/minimal-template) (🦆 Public template)
- **shared-template** → [github.com/Chapter-39/shared-template](https://github.com/Chapter-39/shared-template) (🦆 Public template)

---

## 🎯 Goals

- Reduce friction when starting new projects.
- Unify styles, types, and best practices.
- Keep public repos to leverage free services.
- Iterate on a living ecosystem, not isolated projects.

---

## 🌐 Sites and deployments

- [Main landing](https://c39.vasa.me)
- [Personal landing](https://vasa.me)

---

## 🛠️ Technologies

- **JavaScript / TypeScript**
- **SCSS** for shared styles
- **Node.js** for backend
- **GitHub Actions** for CI/CD
- **Vitest** for unit tests; **Playwright** for E2E

---

## 🧰 Backend

- API template: Node.js + Express 5, TypeScript, Prisma (PostgreSQL).
- Auth: JWT middleware with Zod validation and session token generation.
- Sign in with Apple: OAuth callback, token verification, and S2S notifications.
  - Endpoints: `/auth/apple/callback`, `/auth/apple/token`, `/auth/apple/notifications`.
- User management: `/me/sync` get/update/delete to sync user profile/settings and refresh token.
- AI chat: SSE chat route with retry, price calc, and persistence (conversations/messages).
- Observability: structured logging (nubo-logger), Sentry hooks, and rate limiting where needed.

---

## 🎨 Frontend

- App template: Vue 3 + TypeScript with Vite, Vitest/Playwright, ESLint/Prettier.
  - Mobile: Capacitor-ready (iOS/Android) with example composables.
  - Auth UI: Apple login for web/native and post-login route handler.
- Landing template: Vite-based landing with CI and GitHub Pages deploy.
- Shared template: SCSS styles and TypeScript types, packaged for reuse.
- Design template: minimal design scaffold with lint/format/CI.
- Minimal template: base repo setup (ESLint, Prettier, Husky, lint-staged, CI).

---

## ✅ What’s Done

- Sign in with Apple: web OAuth flow, native token exchange, S2S event handling.
- User management: JWT auth, user sync endpoints (get/put/delete), token refresh.
- Mobile integration: Capacitor setup and example usage in the app template.
- Shared building blocks: reusable SCSS and types via `shared-template`.
- CI/CD: standardized GitHub Actions, test/format/lint workflows, Pages deploy.
- Landing deploy: automated GitHub Pages release with optional CNAME support.

---

## 📌 Status

Work in progress. Live templates, constant iteration.
If you like to explore, jump into any repo — everything is designed to be **copied, adapted, and deployed** with minimal fuss.

---
