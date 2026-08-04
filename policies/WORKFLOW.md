# Core Engineering Workflow

1. **Explore** — inspect repository state, constraints, and authoritative documents.
2. **Shape** — resolve requirements, terminology, business rules, and scope boundaries.
3. **Design** — produce a technical design with explicit seams, failure behavior, and acceptance criteria.
4. **Review the design** — challenge assumptions before implementation begins.
5. **Decompose** — create bounded, dependency-aware tickets or slices.
6. **Implement** — work from the approved design using focused feedback loops.
7. **Checkpoint** — compare the partial implementation with the design before continuing.
8. **Correct** — fix concrete gaps without silently widening scope.
9. **Review implementation** — independently assess standards and specification fidelity.
10. **Review integration** — inspect the combined state for cross-feature and migration gaps.
11. **Validate the candidate** — verify the exact final commit using authoritative evidence.
12. **Publish and hand off** — record the pull request, evidence, risks, and remaining actions.

## Evidence discipline

- Tests are evidence, not the product specification.
- Passing tests do not excuse missing behavior required by the approved design.
- Existing valid evidence should be reused when it applies to the exact candidate.
- Retired or superseded gates must not be recreated casually.
- Release claims must identify the exact commit they support.
