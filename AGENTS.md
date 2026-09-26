# mobile-order-app instructions

<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

## Project

Read `00_docs/brief.md` before planning or changing scope. Read the accepted requirements, design, and `00_docs/validation-plan.md` before implementation or testing.

## Guardrails

- This is a fictional, single-store, takeaway-order verification project unless a separate release decision says otherwise.
- Keep customer, store, kitchen, and administrator permissions separate.
- Treat an order's status and change history as shared business data; do not implement a UI-only state transition without defining its effect on the other roles.
- Do not treat this project as a payment system or collect real customer data.
- Do not commit, push, deploy, publish, or expose secrets without explicit authorization.

## Completion

Report changed files, verification performed, remaining limitations, and the next action.
