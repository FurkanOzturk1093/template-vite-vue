# DeployWise — Vite + Vue Template

A production-ready Vue 3 starter powered by Vite, pre-configured for one-click deployment to your VPS with [DeployWise](https://deploywise.dev).

## What's Included

- Vue 3 with `<script setup>` and TypeScript
- Vite for fast dev and builds
- Optimized for Nginx static hosting

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173).

## Deploy with DeployWise

1. Push this repo to GitHub
2. Open [deploywise.dev/dashboard](https://deploywise.dev/dashboard)
3. Add your VPS → Create a project → Select this repo
4. Click **Deploy**

DeployWise automatically runs `vite build`, serves the `dist/` output via Nginx with SPA routing, gzip compression, and a free SSL certificate.

## Project Structure

```
├── src/
│   ├── App.vue       # Root component
│   ├── main.ts       # Entry point
│   └── components/   # Vue components
├── index.html        # HTML template
├── vite.config.ts    # Vite config
└── package.json
```

## Learn More

- [Deploy Vite App to VPS Guide](https://deploywise.dev/guides/deploy-vite-to-vps)
- [DeployWise Docs](https://deploywise.dev/docs)
- [Vue Documentation](https://vuejs.org)

---

Deployed with [DeployWise](https://deploywise.dev) — free, open source.
