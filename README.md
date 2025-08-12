# Next.js TypeScript Starter Template

A modern [Next.js](https://nextjs.org) starter template featuring a carefully curated tech stack for efficient
development:

- **[TypeScript](https://www.typescriptlang.org/)** -- Type-safe JavaScript development
- **[BiomeJs](https://biomejs.dev/)** -- Fast formatting and linting toolkit
- **[TailwindCss](https://tailwindcss.com/)** -- Utility-first CSS framework
- **[react-icons](https://react-icons.github.io/react-icons/)** -- Popular icon library

This template supports both local development and containerized deployment with Docker.

## Development Setup

Launch the development server using your preferred package manager:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Navigate to [http://localhost:3000](http://localhost:3000) to view your application. The development server includes hot
reloading -- changes to `app/page.tsx` will be reflected immediately.

## Code Quality Commands

The project includes several commands to maintain code quality:

**Linting** -- Analyze code for potential issues:

```bash
pnpm lint
```

**Formatting** -- Apply consistent code formatting:

```bash
pnpm format
```

**Comprehensive Check** -- Format, lint, and organize imports in one command:

```bash
pnpm check
```

**Type Checking** -- Validate TypeScript types:

```bash
pnpm typecheck
```

*All commands support npm, yarn, pnpm, and bun package managers.*

## Docker Deployment

Build Docker images using the provided Makefile commands:

```bash
# Development build
make build-development

# Production build  
make build-production
```

Run the containerized application (only development):

```bash
# Start development stack
make start-development
```

**Requirements:** Ensure your environment file (`.env.development` or `.env.production`) exists in the project root.

## Resources

- [Next.js Documentation](https://nextjs.org/docs) - comprehensive guides and API reference
- [Learn Next.js](https://nextjs.org/learn) - interactive tutorial for beginners
