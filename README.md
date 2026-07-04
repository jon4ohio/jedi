# JEDI

JEDI is an open-source React UI platform built for documentation-heavy, information-dense applications. It provides a governance-first foundation for building scalable interfaces with stable public APIs, design tokens, and reusable documentation. Originally inspired by Meta's Astryx, JEDI has since evolved into an independent platform with its own architecture, design language, governance model, and release process.

## Status

- Architecture frozen
- Foundation Program complete
- Gates 1–3 complete
- Gate 4 intentionally deferred

See:

- [docs/ARCHITECTURE-FREEZE.md](./docs/ARCHITECTURE-FREEZE.md)
- [docs/PLATFORM-HEALTH.md](./docs/PLATFORM-HEALTH.md)

## Quick Start

The reference consumer lives in:

```bash
pnpm dev:docs   # apps/docs-app on port 3001
```

Or explore all apps:

```bash
pnpm install
pnpm verify
pnpm dev:examples    # port 3000
pnpm dev:docs        # port 3001
pnpm dev:playground  # port 3002
```

## Architecture

```
Design Language → Platform Foundation → Design System → Applications
```

## Packages

| Package | Capability |
|---------|------------|
| `@jedi/tokens` | Design Language |
| `@jedi/themes` | Theme Engine |
| `@jedi/stylex` | Styling Infrastructure (StyleX) |
| `@jedi/foundation` | Layout System |
| `@jedi/react` | Interactive Components |
| `@jedi/icons` | Icons |
| `@jedi/patterns` | Application Patterns |
| `@jedi/docs` | Documentation Components |
| `@jedi/a11y` | Accessibility |
| `@jedi/motion` | Motion |

## Development

```bash
pnpm install
pnpm verify    # test + build + boundaries + metrics
```

## Governance

- [CONSTITUTION.md](./docs/CONSTITUTION.md)
- [ARCHITECTURE.md](./docs/ARCHITECTURE.md)
- [ARCHITECTURE-FREEZE.md](./docs/ARCHITECTURE-FREEZE.md)
- [PLATFORM-HEALTH.md](./docs/PLATFORM-HEALTH.md)
- [POSITIONING.md](./docs/POSITIONING.md)
- [ROADMAP.md](./docs/ROADMAP.md)
- [APPS.md](./docs/APPS.md)
- [LIFECYCLE.md](./docs/LIFECYCLE.md)
- [CAPABILITY-MATRIX.md](./docs/CAPABILITY-MATRIX.md)
- [ACCEPTANCE.md](./docs/ACCEPTANCE.md)
- [UPSTREAM.md](./docs/upstream/UPSTREAM.md)
