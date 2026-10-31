# abhi-iedc

Vite + React app rendering the ThreeUI **KageLandingPage** component from its exact registered source.

## Stack

- [@designcodeio/threeui](https://www.npmjs.com/package/@designcodeio/threeui) `1.2.0` — provides `KageLandingPage` and the packaged page files
- React 18 + TypeScript + Vite

## Structure

- `src/Scene.tsx` — the configured component usage (typography props)
- `public/landing-pages/` — the byte-exact packaged document and assets, copied from `node_modules/@designcodeio/threeui/lib-dist/assets/` as the package README prescribes (canonical `kage.html` SHA-256 `c8e06b90397a…`)

## Develop

```bash
npm install
npx vite
```

## Build

```bash
npm run build   # outputs dist/
```

Deployed on Vercel as project `abhi-iedc` → https://abhi-iedc.vercel.app
