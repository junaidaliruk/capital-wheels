# Contributing

Thanks for helping improve Capital Wheels.

## Setup

```bash
bun install
bun run dev
```

## Before you open a pull request

```bash
bun run lint     # biome check
bun run format   # biome format --write
bun run build    # verify the production build
```

All three must pass.

## Guidelines

- Follow the existing Next.js App Router conventions — server components by default, `"use client"` only where interaction requires it.
- Keep Tailwind classes readable; extract repeated patterns into components.
- One focused change per pull request.
- Describe the problem you are solving in the PR body.

## Commit messages

Use the imperative mood: `add booking date picker`, not `added booking date picker`.
