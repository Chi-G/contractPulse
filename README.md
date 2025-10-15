# ContractPulse — Contract Management & Analytics (React + Vite)

![ContractPulse screenshot](/assets/images/screenshot.png)

A modern single-page application for contract lifecycle management, analytics, and workflow automation. Built with React, Tailwind CSS and Vite. This repo contains the frontend SPA; the backend can be attached using Laravel, NestJS, FastAPI, or serverless APIs depending on your preference.

---

## Quick start (developer)

Requirements

- Node.js 16+ (LTS recommended)
- npm or yarn

Install and run locally

```powershell
npm ci
npm run dev
```

Build for production

```powershell
npm run build
npm run serve
```

Open the app at: [http://localhost:5173](http://localhost:5173) (or the port printed by Vite)

---

## Project structure (important files)

- `index.html` — HTML template and favicon
- `src/main.jsx` — app entry (mounts React)
# ContractPulse

ContractPulse is a frontend-only React application demonstrating contract dashboards, analytics widgets, and workflow UIs using demo/mock data. The repo contains no backend, authentication, or persistent storage.

Stack:
- React 18
- Vite
- Tailwind CSS
- Redux Toolkit (state) and React Router

Quickstart:

```powershell
npm ci
npm run dev
```

Recommended backend (brief):
Laravel (for fast, batteries-included APIs) or NestJS + Prisma (for TypeScript end-to-end). This repository is frontend-only and uses demo data only.
