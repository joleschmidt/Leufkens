# System Patterns

## Architecture
The project follows a **Static Site Generation (SSG)** architecture using **Astro**.
- **Pages**: Defined in `src/pages/` (file-based routing).
- **Layouts**: `src/layouts/Layout.astro` provides the common HTML shell (Head, Header, Footer).
- **Components**: UI blocks in `src/components/` used to build pages.

## Component Structure
- **Presentation**: Components are primarily presentational (HTML/CSS via Tailwind).
- **Interactivity**: Minimal client-side JavaScript. React is available (`@astrojs/react`) but usage appears limited to static rendering or simple interactions so far.

## Design Patterns
- **Utility-First CSS**: Tailwind CSS for all styling.
- **Props Interface**: TypeScript interfaces used in components (e.g., `Props` in `Layout.astro`) to ensure type safety.
- **Responsive Design**: Mobile-first approach using Tailwind's breakpoints (`md:`, `lg:`).

## File Organization
```
src/
├── components/   # Reusable UI sections (Contact, Header, Team, etc.)
├── layouts/      # Global page wrappers
├── pages/        # Route definitions
└── styles/       # Global styles (Tailwind imports)
```
