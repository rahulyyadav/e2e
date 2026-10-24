---
'e2e': minor
---

`locator.or(other)` unions two locators. The result matches the nodes either locator matches, each node once and in document order: `expect(screen.getByRole('tab', 'Discover').or(screen.getByRole('tab', 'Odkrywaj'))).toBeVisible()` waits for one tab under either name. Actions, reads, and single-node assertions on a union still require exactly one match, and both branches are named in every failure message and report label.
