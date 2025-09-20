# Chapter 39

**Chapter 39** is a set of templates and utilities to accelerate app development.
The goal is to keep a common, modular foundation so we don't reinvent the wheel on every project.

---

## 🔹 Repositories

[**backend-template**](https://github.com/Chapter-39/backend-template) - Minimal, opinionated starter kit for modern Node.js backends.  
[**app-template**](https://github.com/Chapter-39/app-template) - Hybrid mobile app template using Vue 3, Vite, and Capacitor.  
[**shared-template**](https://github.com/Chapter-39/shared-template) - Shared styles and types for web and mobile projects.  
[**landing-template**](https://github.com/Chapter-39/landing-template) - Vite-based landing page template with GitHub Pages deploy.  
[**design-template**](https://github.com/Chapter-39/design-template) - Design system scaffold with SCSS, linting, formatting, and CI.  
[**minimal-template**](https://github.com/Chapter-39/minimal-template) - Minimal template with ESLint + Prettier and CI via GitHub Actions.

---

## 🎯 Goals

- Reduce friction when starting new projects.
- Unify styles, types, and best practices.
- Keep public repos to leverage free services.
- Iterate on a living ecosystem, not isolated projects.

---

## 🌐 Sites and deployments

- [Landing page](https://c39.vasa.me)
- [Web app](https://wa-c39.vasa.me)
- [Personal page](https://vasa.me)

---

## 🛠️ Technologies

- **TypeScript**
- **SCSS** for shared styles
- **Node.js** and **Express** for backend
- **Prisma** with **PostgreSQL** for database
- **Vue 3** for frontend
- **Capacitor** for mobile (iOS/Android)
- **GitHub Actions** for CI/CD
- **Vitest** for unit tests; **Playwright** for E2E

---

## 🧰 Backend

- API template: Node.js + Express 5, TypeScript, Prisma (PostgreSQL).
- Auth: JWT middleware with Zod validation and session token generation.
- Sign in with Apple: OAuth callback, token verification, and S2S notifications.
  - Endpoints: `/auth/apple/callback`, `/auth/apple/token`, `/auth/apple/notifications`.
- User management: `/me/sync` get/update/delete to sync user profile/settings and refresh token.
- Observability: structured logging (logger), Sentry hooks, and rate limiting where needed.

---

## 🎨 App

- App template: Vue 3 + TypeScript with Vite, Vitest/Playwright, ESLint/Prettier.
  - Mobile: Capacitor-ready (iOS/Android) with example composables.
  - Auth UI: Apple login for web/native and post-login route handler.

---

## 🧺 Utilities

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
