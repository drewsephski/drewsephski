# Drew Sepeczi

**Full-stack product developer · Applied AI · Chicago**

I'm an early-career developer building useful products with React, Next.js, and TypeScript. My work connects product UX with APIs, authentication, databases, and AI integrations.

[Portfolio](https://drewsepeczi.xyz) · [LinkedIn](https://www.linkedin.com/in/drewsepeczi/)

## Three projects to start with

### [Nodebase](https://github.com/drewsephski/nodebase) — visual AI workflow builder

I built a drag-and-drop workflow editor with AI and MCP tool integrations, streamed execution progress, and saved run history.

- **Engineering focus:** connecting a visual graph to workflow execution, showing node-level results, and handling interrupted runs and authorization steps.
- **Stack:** Next.js, TypeScript, React Flow, LangGraph, Convex.
- **Status:** sunset; the successor is [Nodebrowser](https://github.com/drewsephski/nodebrowser). Nodebase remains available as a record of the work.

[![Nodebase GitHub stars](https://img.shields.io/github/stars/drewsephski/nodebase?style=flat)](https://github.com/drewsephski/nodebase/stargazers)

[Execution UI](https://github.com/drewsephski/nodebase/blob/main/hooks/useWorkflowExecution.ts) · [Run persistence](https://github.com/drewsephski/nodebase/blob/main/convex/executions.ts)

### [FormSquid](https://github.com/drewsephski/form-squid) — AI forms with source-code export

I built a prompt-to-publish form builder with hosted submissions, a response inbox, signed webhooks, and exportable React Hook Form + Zod components through a shadcn registry.

- **Engineering focus:** keeping generated form behavior consistent with server validation, isolating published versions, and delivering webhooks with signatures, bounded retries, and destination checks.
- **Stack:** Next.js, React, TypeScript, Better Auth, Drizzle, Neon Postgres.
- **Validation:** the repository includes generated-code acceptance tests and a clean-consumer shadcn MCP installation check.

[Product](https://formsquid.com) · [Webhook delivery](https://github.com/drewsephski/form-squid/blob/main/server/webhooks/deliver.ts) · [Export acceptance tests](https://github.com/drewsephski/form-squid/blob/main/app/lib/__tests__/exported-form-acceptance.test.ts)

### [Homeshare](https://github.com/drewsephski/billtracker) — shared household bills

I built a roommate bill tracker for recurring bills, split balances, and recorded contributions. All five members of my household use it regularly.

- **Engineering focus:** household-scoped access, transactional writes, and database constraints that keep bill splits equal to the total.
- **Stack:** Next.js, React, strict TypeScript, Neon Postgres, Drizzle, managed Neon Auth.
- **Applied AI:** contribution suggestions require human confirmation before recording a change.

[Product](https://homeshare.dev) · [Household access](https://github.com/drewsephski/billtracker/blob/main/lib/server/households.ts) · [Financial invariants](https://github.com/drewsephski/billtracker/blob/main/drizzle/0002_financial_invariants.sql)

## Background

Studying AI & Cloud at Harper College; A.A.S. expected in 2027. I'm interested in early-career full-stack, product engineering, and applied AI opportunities.

Additional work includes [Menace Voice](https://github.com/drewsephski/menace-voice), built on the upstream Dograh project. My contributions include the redesigned UX and product shell, Stripe billing, and persistent cloud backend storage.
