# ts-template

Starter template for bootstrapping Typescript projects.

## Tools

- **TypeScript** - Type-safe JavaScript development
- **ESLint** - Code linting with TypeScript support
- **Prettier** - Code formatting
- **Vitest** - Fast unit testing with coverage
- **Husky** - Git hooks for quality gates
- **Commitlint** - Conventional commit message validation
- **PNPM** - Fast, disk space efficient package manager

## Scripts

| Command | Description |
|---------|-------------|
| `pnpm build` | Compile TypeScript to JavaScript |
| `pnpm test` | Run tests with Vitest |
| `pnpm lint` | Lint code with ESLint |
| `pnpm format` | Format code with Prettier |
| `pnpm typecheck` | Type-check without emitting files |

## Git Workflow

This template enforces quality through git hooks:

- **Pre-commit**: Runs linting and formatting
- **Commit-msg**: Validates commit messages follow conventional format

### Commit Message Format

Follow the [Conventional Commits](https://conventionalcommits.org/) specification:

```
type(scope): description

feat: add new feature
fix: resolve bug
docs: update documentation
test: add tests
refactor: improve code structure
```

## License

UNLICENSED - This is a template repository