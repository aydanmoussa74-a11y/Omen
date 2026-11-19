# Omen

**A mobile-first AI engineering workstation.**

Omen brings projects, code, agent workflows, research, diagnostics and Git context into one touch-first engineering environment.

## Status

Early product foundation. The interface is being built in vertical slices. Anything not connected to a real provider, repository API or execution environment is explicitly presented as a local preview — never as a completed operation.

## Stack

- React + TypeScript + Vite
- Lucide icons
- CSS design tokens and responsive layouts
- Provider and execution adapters will be isolated from the UI

## Run locally

```bash
npm install
npm run dev
```

## Build checks

```bash
npm run typecheck
npm run build
```

## Product principles

- Mobile-first, keyboard-aware and accessible.
- Preserve project context across tools.
- Explicit approvals for consequential actions.
- No fake terminal output, repository writes, agent completion or verification.
- Provider-agnostic architecture.
