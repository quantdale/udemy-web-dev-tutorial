# web-dev-tutorial

A collection of small static web-development exercises from a Udemy/App Brewery-style learning track. The current repository is a course/practice workspace, not one production application.

## Current contents

The root currently contains a simple portfolio-style `index.html`, exercise/solution pages, a `public/` directory with linked practice pages, local assets, and agent/planner adapters. Some practice pages reference externally hosted images, so the site is not fully self-contained offline.

There is currently no `package.json`, JavaScript build system, backend service, automated test suite, or root dependency-install step.

## Running the exercises

Open `index.html` or the individual HTML files directly in a browser. A simple static-file server may also be used when browser/security behavior makes `file://` inconvenient.

Git history includes a GitHub Pages redeploy trigger, but the existence of that historical commit is not proof that Pages is currently enabled, deployed, or serving the latest commit. Check GitHub Pages/deployment state separately before making a live-site claim.

## Validation

For changes to these static exercises:

- inspect the affected HTML and local links/assets;
- render the relevant page in a browser when practical;
- distinguish local files from remote image/content dependencies;
- do not claim automated tests or a build PASS when no such system exists.

## Learning-project boundary

Preserve exercise instructions/TODOs and solutions as learning context unless a task explicitly asks to clean them up. Do not automatically convert course exercises into React/Vite/other frameworks merely because a modern stack would be possible.

Agents should read `AGENTS.md` and `.agent/STATE.md` before substantial work.
