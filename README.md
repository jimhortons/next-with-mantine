#  Next.js with Mantine UI
This is a starter kit for using Next.js with the Mantine UI library which includes more than 120 customizable components and hooks.

## Starter Kit Features

This starter kit comes with several essential features:

- Server side rendering setup for Mantine
- Color scheme is stored in cookie to avoid color scheme mismatch after hydration
- Storybook with color scheme toggle
- Jest testing library
- ESLint

## Build and Development Scripts
- `dev` – start dev server
- `build` – bundle application for production
- `export` – exports static website to `out` folder
- `analyze` – analyzes application bundle with [@next/bundle-analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)



## Storybook Scripts
- `storybook` – starts storybook dev server
- `storybook:build` – build production storybook bundle to `storybook-static`
- `prettier:write` – formats all files with Prettier

## Testing Scripts
- `typecheck` – checks TypeScript types
- `lint` – runs ESLint
- `prettier:check` – checks files with Prettier
- `jest` – runs jest tests
- `jest:watch` – starts jest watch
- `test` – runs `jest`, `prettier:check`, `lint` and `typecheck` scripts


