# Main ref case

Tests that the risk check and the secret scan run from `main` of
`specklesystems/.github` (atlas change-gate rollout ADR-0004).

Expected: `check / Evaluate` runs the shared workflow at the commit `main` of
`specklesystems/.github` has, the risk check posts the yellow floor comment on
this file and writes a `risk-check` status that asks for an approver color, and
`secret-scan / scan` passes.
