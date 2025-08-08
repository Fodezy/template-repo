# MVP Test Plan

## Scope
Core happy path: <describe>

## Types
- Unit: target 70%+ on core modules
- Integration: DB/API boundaries for A, B
- E2E: 3 flows (e.g., signup, create X, share Y)
- Non-functional: P95 < 300ms on endpoint Z

## Environments
PR env per branch, staging, prod

## Tooling
pytest/jest + Playwright; coverage gate 70%; error tracking in Sentry (or similar)

## Exit Criteria
0 Sev-1/2, 95% passing E2E, rollback tested
