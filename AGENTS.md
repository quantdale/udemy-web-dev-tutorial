# web-dev-tutorial — Agent Instructions

This is the canonical repository-level contract for agents working on `quantdale/udemy-web-dev-tutorial`.

## Repository identity

This repository is a collection of static HTML web-development learning exercises. It is not a single production application. The current root has no npm/package manifest, bundler, backend, or automated test suite.

Do not invent a toolchain or infer a framework from generic “web development” terminology.

## Required reading

1. `README.md` and `.agent/STATE.md`.
2. `.agent/PLANNER_HANDOFF.md` and any genuinely active `.agent/EXECUTION_PROMPT.md`.
3. The specific HTML/public/assets files for the exercise being changed, including preserved TODO/instruction comments.
4. Recent Git history when deployment/GitHub Pages state matters.

## Learning-scope discipline

- Treat course TODOs, sample/solution pages, and progressive exercises as instructional artifacts, not dead code to normalize away.
- Do not migrate exercises to React/Vite/TypeScript/CSS frameworks or introduce a package manager unless the task explicitly changes the exercise scope.
- Keep unrelated exercises independent; a cleanup in one page does not require a repo-wide redesign.
- External image URLs are remote dependencies. Do not describe a page as fully offline/self-contained unless the assets are actually local.

## Validation and deployment claims

There is no root automated build/test system at this checkpoint. Validate affected pages structurally and in a browser when available, checking links and assets relevant to the change.

Git history contains a GitHub Pages redeploy commit, but historical deployment activity is not current deployment evidence. Check live repository/Pages state before stating that a site is deployed or current.

## Content discipline

These exercises may contain personal portfolio-style wording and course-derived prompts. Do not invent or embellish personal facts, and do not replace course content wholesale unless explicitly requested.

## Documentation and Git safety

Update the root index docs when the repository gains/removes major exercises or a real toolchain. Preserve historical learning context.

Do not discard unrelated work, rewrite history, force-push, or perform broad “modernization” as incidental cleanup. Keep commits scoped and reviewable.
