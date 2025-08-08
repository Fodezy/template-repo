# Idea → Product Starter

A lightweight playbook and templates to take a concept from idea to a shippable MVP, then iterate without chaos.

## What's inside
- **docs/Idea-to-Product-OnePager.pdf** — concise lifecycle reference.
- **templates/** — copy‑paste templates (PRD, ADR, Spike, Risk Register, Test Plan, Launch Checklist).

## Suggested Workflow
1. **Ideation & Validation (3–10 days)** — write an *Idea Brief*, test assumptions with users or a landing page.
2. **Scope & Plan (2–5 days)** — define your MVP and write a lightweight **PRD**.
3. **Design & Architecture (3–7 days)** — wireframes, stack choice, CI/testing scaffold, initial **ADRs**.
4. **Build Iterations (1–2 weeks)** — Plan → Build → Test → Review → Demo → Retro; ship behind flags.
5. **Pre‑Launch Testing (2–7 days)** — regression, UAT, perf/security sanity, rollout plan.
6. **Launch & Feedback** — canary rollout, analytics & error tracking, triage.
7. **Post‑Launch Iteration** — prioritize with RICE, reserve ~15% for tech debt, monthly roadmap review.

## Decision Aid: Pivot vs Continue
- **Unblocks critical MVP risk?** Spike next sprint (timebox) and decide via ADR.
- **Current approach fails AC/perf?** Spike → ADR → plan migration with flags.
- **Pushes MVP beyond 6 weeks?** Defer unless existential.

## Testing Strategy (CI Gates)
- Unit → Integration → Contract → E2E (few, critical).
- CI: lint/format, tests, coverage ≥70% (non‑decreasing), build/scan, optional SAST/DAST.

## Templates
See **/templates** for ready‑to‑use docs:
- PRD.md
- ADR.md
- SPIKE.md
- RISK_REGISTER.md
- MVP_TEST_PLAN.md
- LAUNCH_CHECKLIST.md

---

*Generated on 2025-08-08.*
