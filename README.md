# Personal Website

A minimal personal website built with React + TypeScript

## Tech Stack

- React
- TypeScript
- React Compiler
- rolldown-vite
- pnpm

## Commands

```
pnpm install - Install dependencies
pnpm dev - Start development server
pnpm build - Build for production
```

## Deployment

The site is deployed to a VPS.

- nginx is used as a reverse proxy.
- The server listens for GitHub webhooks.
- On pushes to master, the VPS automatically pulls the latest changes and updates the site.
