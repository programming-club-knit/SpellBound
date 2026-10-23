# Contributing to Spellbound

Welcome to Hack the Web! Contributions should improve one focused part of the game while preserving its atmospheric, accessible mystery-adventure feel.

## Workflow

1. Fork `prathmyx/SpellBound` on GitHub.
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/SpellBound.git`.
3. Create a branch from the default branch. Use `fix/issue-short-name` or `feat/short-name`, for example `fix/inventory-keys`.
4. Install dependencies with `npm install`.
5. Make the smallest change that fully addresses one issue.
6. Run `npm run build` and manually test the affected gameplay in `npm run dev`.
7. Push your branch and open a pull request against `prathmyx/SpellBound:main`.
8. Link the issue in the PR body with `Closes #NUMBER` when appropriate.

## Pull request checklist

- [ ] The PR addresses one issue and links it.
- [ ] The affected interaction was tested manually.
- [ ] `npm run build` passes.
- [ ] Keyboard focus and responsive layouts remain usable.
- [ ] The description explains the problem, fix, and testing performed.
- [ ] No unrelated files or dependencies were added.

## Review and merge

Maintainers review correctness, clarity, accessibility, and scope. Please respond to review feedback in the same PR and keep follow-up commits focused. A PR may be merged once required checks pass and a maintainer approves it.

## Hack the Web scoring

The six challenge issues are worth **135 points total**:

| Challenge | Points |
|---|---:|
| Inventory item rendering | 10 |
| Stale potion and interaction state | 15 |
| Shared game state through Context | 20 |
| Ghost timer cleanup | 25 |
| Room exploration rendering performance | 30 |
| Restore progress after refresh | 35 |

Choose a challenge from the [GitHub Issues tab](https://github.com/prathmyx/SpellBound/issues). Points are associated with the listed challenge, not the size of the diff. A merged, accepted PR is the intended completion milestone; confirm event-specific rules with the organizers.
