# Solo‑Dev Lite Template

A dead-simple template for solo projects. Minimal folders, one issue template, and two tiny docs.
Use this to start fast without heavy process.

## What's inside
- `docs/PRD_TEMPLATE.md` — one-page spec with acceptance criteria
- `docs/ADR_TEMPLATE.md` — one-page architecture decision memo
- `docs/ROADMAP.md` — Now / Next / Later (keep it short)
- `.github/ISSUE_TEMPLATE/simple.yml` — single generic issue form
- `LICENSE` — MIT (replace the name with yours)

## Quick start
1. Push this repo to GitHub and mark it as a **Template Repository** (Settings → Template repository).
2. Start a new project by clicking **Use this template**, or via CLI:
   ```bash
   gh repo create YOUR_USER/my-new-project --template YOUR_USER/solo-dev-lite --private --clone
   ```
3. Open `docs/ROADMAP.md` and jot down **Now / Next / Later**.
4. For each feature/bug/spike, open **one Issue** using the simple template.
5. If a spike changes direction, write **one ADR** (5 minutes) to capture the decision.

## Five simple rules
1. New idea → one Issue (label: feature, bug, or spike).
2. Spikes end with a decision → `docs/ADR_TEMPLATE.md` copy, fill, commit.
3. Roadmap stays short (3–9 bullets total).
4. Ship the smallest thing that meets the PRD.
5. After a mini-release, note 3 bullets: keep / stop / try (in the issue).

---

*Generated on 2025-08-08.*
