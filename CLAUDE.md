# CLAUDE.md - Project Guidelines

## Commands
- `npm install` - Install dependencies
- `npm run dev` - Start development server at localhost:4321
- `npm run build` - Build production site to ./dist/
- `npm run preview` - Preview production build locally
- `npm run astro ...` - Run Astro CLI commands

## Code Style Guidelines
- **Framework**: Astro with Tailwind CSS
- **TypeScript**: Follow strict typing with interfaces for component props
- **Naming Conventions**: 
  - Components: PascalCase (e.g., `Navbar.astro`)
  - Variables/Functions: camelCase
  - CSS classes: kebab-case via Tailwind utilities
- **Imports**: Group by type (layouts, components) with local imports last
- **Component Structure**: 
  - Frontmatter script section first (`---`)
  - Component template second
  - Optional styles last
- **Tailwind CSS**: Use utility classes with custom theme values for brand colors/fonts
- **Error Handling**: Use TypeScript nullish coalescing and optional chaining
- **Formatting**: Use meaningful indentation (2 spaces) and consistent spacing