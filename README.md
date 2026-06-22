# 4ui

Open-code Svelte 5 components for operational and data-heavy interfaces.

4ui will begin with accessible foundations, then grow into components for realtime data,
analytics, industrial dashboards, formulas, alarms, asset hierarchies, and other demanding
product interfaces.

## Status

The project is in its foundation phase. Public APIs and licensing terms are not final.

## Tooling

- Svelte 5 and SvelteKit
- TypeScript
- `@sveltejs/package`
- Storybook with accessibility checks
- Vitest browser component tests
- Playwright end-to-end tests
- ESLint and Prettier

## Development

```sh
pnpm install
pnpm dev
```

Run the component workshop:

```sh
pnpm storybook
```

Validate the project:

```sh
pnpm check
pnpm lint
pnpm test:unit
pnpm build
pnpm build-storybook
```

Playwright browsers are installed separately:

```sh
pnpm exec playwright install chromium
```

## Structure

```text
src/lib/       Public package source
src/routes/    Documentation and showcase application
.storybook/    Isolated component development
```

Everything exported from `src/lib/index.ts` becomes part of the package API.

## Licensing

No public software license has been granted yet. A dual-license model is planned:

- free for personal and noncommercial use
- paid commercial license for business and client use

The final terms will be reviewed before the first public component release.
