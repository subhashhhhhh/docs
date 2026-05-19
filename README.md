# Fastlytics documentation

This repository contains the Mintlify documentation site for Fastlytics.

## What is in here

- `docs.json` for site navigation and branding
- `*.mdx` pages for product, platform, and API documentation
- `logo/` and `favicon.svg` for site branding

## Local preview

Install the Mintlify CLI if needed:

```bash
npm i -g mint
```

Run the preview from the docs repository root:

```bash
mint dev
```

The preview is available at `http://localhost:3000` by default.

## Validation

```bash
mint broken-links
mint validate
```

## Writing guidance

- Match the terminology in `AGENTS.md`
- Use root-relative internal links without file extensions
- Keep pages factual and workflow-oriented
- Add a TODO comment for any production detail that still needs verification

## Publishing

Mintlify deploys changes automatically after the connected repository updates on its default branch.
