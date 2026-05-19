# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "race workspace" for the main analysis surface inside an event page.
- Use "session replay" for the synced track-position replay view.
- Use "Free" and "Pro" exactly when discussing plans.
- Use "season" and "race weekend" instead of generic sports terms like "match" or "event" unless the route or API name specifically uses `event`.
- Use "driver" and "team" consistently. Do not switch to "player" or "constructor" unless the context is official standings terminology.

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise and technical
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Prefer product workflows over feature marketing
- Avoid promising capabilities that are marked "coming soon" in the product
- Treat API docs as implementation-aware documentation unless a stable public contract is explicitly introduced

## Content boundaries

- Document the public product, contributor workflows, and the current web-app API surface.
- Do not document internal admin tooling or unpublished operational procedures.
- Flag uncertain production details such as canonical worker domains or future pricing tiers with TODO comments instead of guessing.
