---
'@e2e-dev/web': minor
---

Resolves `locator.or(other)` inside the page through Playwright's own locator union, in the same round trip as any other locator. Requires `e2e` 0.18.0 or later. A union whose branch is a `getByDisplayValue` query, an exact-string `getByLabel`, or reaches a nested frame fails with `UNSUPPORTED_CAPABILITY`.
