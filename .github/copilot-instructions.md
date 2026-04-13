# DH101 Copilot Instructions

## Project overview
- Static course site: HTML pages in docs/ link to Markdown content in docs/makes and docs/reflections.
- Primary entry points: docs/index.html (home) and docs/projects.html (projects list).
- A second HTML copy exists under docs/docs/ (docs/docs/index.html, docs/docs/projects.html); keep content consistent if you update one.

## Content conventions
- Weekly content lives in docs/makes/weekXX.md and docs/reflections/weekXX.md (see existing weeks for structure).
- Follow the Markdown style guide in docs/markdown-guide.md (headings, lists, links, image paths).
- Use relative links (example: makes/week03.md in docs/index.html).
- Keep filenames lowercase with hyphens and avoid spaces (per docs/markdown-guide.md).

## AI usage documentation
- AI usage notes are templated in ai-log/template-ai-log.md; keep new entries aligned with that format if asked.

## Workflow notes
- No build system or test runner is present; edits are direct to HTML/Markdown files under docs/.
- Preview Markdown locally in VS Code; HTML pages depend on correct relative paths.

## Pointers for common edits
- Update navigation links in docs/index.html and docs/projects.html together to keep headers in sync.
- When adding a new week, add a card to docs/projects.html and create the matching docs/makes/weekXX.md and/or docs/reflections/weekXX.md.