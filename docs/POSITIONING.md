# JEDI Positioning

Canonical source for portfolio copy, conference proposals, LinkedIn, résumé, interviews, and future documentation.

## Overview

JEDI is an open-source React UI platform for documentation-heavy, information-dense applications. It ships with a governance-first architecture — design tokens, stable public APIs, reusable documentation components, and a validation pipeline — so teams can build scalable interfaces without reinventing platform infrastructure.

## What JEDI is

A capability-driven UI platform composed of 10 packages:

- **Design Language** — `@jedi/tokens`, `@jedi/themes`, `@jedi/stylex`
- **Design System** — `@jedi/foundation`, `@jedi/react`, `@jedi/icons`, `@jedi/patterns`, `@jedi/docs`
- **Platform utilities** — `@jedi/a11y`, `@jedi/motion`

Three dogfood applications validate the platform: `apps/examples`, `apps/docs-app`, `apps/playground`.

Governance is first-class: Constitution, ADRs, architecture freeze, platform health metrics, and boundary enforcement.

## Design philosophy

- **Design Language ≠ Design System** — tokens express the language; components express the system
- **Tokens before components** — no component ships without token backing
- **Capability-driven architecture** — packages map to capabilities, not convenience
- **Public APIs are contracts** — breaking changes require ADR and version consideration
- **Composition over configuration** — build from layout primitives, not wrappers

## Relationship to Astryx

JEDI was originally inspired by Meta's Astryx. Astryx remains an optional architectural reference for patterns in token cascade, accessibility, and component anatomy.

JEDI does not depend on Astryx at runtime. Zero `@astryxdesign/*` imports. JEDI owns documentation-heavy, information-dense applications — a different scope than Astryx's breadth.

## Relationship to SeamKit

SeamKit demonstrates enterprise design system governance at scale within a company — token architecture, component libraries, adoption metrics, and cross-team coordination.

JEDI demonstrates the same engineering discipline applied to an independent open-source platform — constitution, ADRs, release engineering, and public API contracts.

These are complementary stories: enterprise DS governance (SeamKit) and OSS platform architecture (JEDI).

## Why it exists

Documentation-heavy applications — portfolios, research platforms, evidence systems, technical documentation — need:

- Stable public APIs that don't leak internal package boundaries
- A token architecture that evolves independently of components
- Reusable documentation components (evidence panels, ADR viewers, token galleries)
- Governance that prevents architecture drift as the platform grows

JEDI provides that foundation.

## Who it is for

- **Platform contributors** extending JEDI packages and governance
- **Application builders** consuming JEDI via public APIs only
- **Documentation-heavy product teams** needing evidence, research, and technical content UI

## Portfolio narrative

> Built on JEDI, an open-source UI platform I created for documentation-heavy applications. JEDI ships with its own design language, governance model, architecture, validation pipeline, and release process — 10 packages, 40 tests, and reference applications that consume only public APIs.

## Short GitHub description

Open-source React UI platform for documentation-heavy applications. Independent design language, governance, and architecture.
