# Capital Wheels

<p align="center">
  <a href="https://capital-wheels.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-capital--wheels.vercel.app-2F80ED?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16.4-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-19.3-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/Biome-Lint_/_Format-60A5FA?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
</p>

## Overview

**Capital Wheels** is a car rental web application built with the Next.js App Router. It ships a modern, responsive UI styled with Tailwind CSS 4 and keeps the codebase consistent with Biome.

**Live:** https://capital-wheels.vercel.app

## Tech stack

| Layer | Choice |
|---|---|
| Framework | Next.js 16 (App Router) |
| UI | React 19 |
| Styling | Tailwind CSS 4 (Turbopack plugin) |
| Lint & format | Biome |
| Package manager | Bun |
| Compiler | React Compiler (Babel plugin) |

## Getting started

Prerequisites: [Bun](https://bun.sh) 1.4+.

```bash
bun install
bun run dev
```

Open http://localhost:3000.

## Scripts

| Command | Description |
|---|---|
| `bun run dev` | Start the Next.js dev server |
| `bun run build` | Production build |
| `bun run start` | Serve the production build |
| `bun run lint` | `biome check` across the repo |
| `bun run format` | `biome format --write` |

## Code style

Formatting and linting are handled by Biome (`biome.json`). Run `bun run lint` before opening a pull request.

## License

MIT
