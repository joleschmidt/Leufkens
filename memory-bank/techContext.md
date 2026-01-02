# Tech Context

## Technology Stack
- **Framework**: [Astro](https://astro.build/) v5.16.6
- **UI Library**: [React](https://react.dev/) v19 (integrated via `@astrojs/react`)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) v4.1.18
- **Icons**: [Lucide React](https://lucide.dev/) v0.562.0
- **Package Manager**: npm

## Development Environment
- **Build Tool**: Vite (underlying Astro).
- **Language**: TypeScript (implied by `tsconfig.json` and `.astro` usage).

## Configuration
- `astro.config.mjs`: Astro configuration.
- `tailwind.config.mjs`: (Likely handles Tailwind config, or it's v4 zero-config/CSS-based).
- `tsconfig.json`: TypeScript compiler options.

## Dependencies
Key dependencies from `package.json`:
- `astro`
- `@astrojs/react`
- `tailwindcss`
- `@tailwindcss/vite`
- `lucide-react`
- `clsx`, `tailwind-merge` (for class manipulation)
