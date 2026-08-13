# Rsbuild project

## Setup

Install the dependencies:

```bash
pnpm install
```

## Get started

Start the dev server, and the app will be available at [http://localhost:3000](http://localhost:3000).

```bash
pnpm run dev
```

Build the app for production:

```bash
pnpm run build
```

Run local feedback-loop checks (same checks as PR flow):

```bash
pnpm run feedback:loop
```

Preview the production build locally:

```bash
pnpm run preview
```

## Git hooks

Pre-push hook runs `pnpm run feedback:loop` automatically.

If hooks are not active locally, run:

```bash
git config core.hooksPath .githooks
```

## Learn more

To learn more about Rsbuild, check out the following resources:

- [Rsbuild documentation](https://rsbuild.rs) - explore Rsbuild features and APIs.
- [Rsbuild GitHub repository](https://github.com/web-infra-dev/rsbuild) - your feedback and contributions are welcome!
