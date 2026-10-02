# Crowsi site content

## Site content

- Audience: global. English is served at `/`; Japanese is served at `/ja/`.
- Publication boundary: general network and infrastructure engineering information and public work only; no connection to or change of a live environment.

## Local verification

```bash
pnpm install --offline --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

Run `pnpm dev` only as a foreground loopback preview and stop it with Ctrl+C.
