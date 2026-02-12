# Rainy MaTE Documentation

This folder contains the Mintlify documentation site for Rainy MaTE.

## Local development

From `rainy-docs`, run:

```bash
mint dev
```

Preview opens at `http://localhost:3000`.

## Validation

Run before publishing documentation changes:

```bash
mint broken-links
mint validate
```

## Content structure

- `welcome.mdx`, `quickstart.mdx`: onboarding pages
- `users/`: operator and end-user workflows
- `developers/`: engineering setup and release docs
- `reference/`: security, tool, and policy references
- `features/`: product area guides
- `components/`: Tahoe design system documentation

## Deployment

Mintlify deploys documentation changes from the connected repository branch.