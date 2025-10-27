# Contributing to gig.ly

## Branching
Use short, issue-keyed branches:
- `feature/GIG-<key>-<slug>` for new work
- `fix/GIG-<key>-<slug>` for bug fixes
- `docs/GIG-<key>-<slug>` for documentation
- `chore/GIG-<key>-<slug>` for tooling/infra

**Examples**
- `feature/GIG-28-initialize-swiftui`
- `docs/GIG-31-contributing-branching`

## Commits
- Include the Jira key in commits:  
  `GIG-28 feat: initialize SwiftUI app scaffold`
- Keep messages concise; use conventional prefix when helpful: feat, fix, docs, chore, refactor, test.

## Pull Requests
- Target branch: `main` (PRs only; no direct pushes).
- Title includes Jira key, e.g. `GIG-28 Initialize SwiftUI app scaffold`.
- Add a 1–3 sentence description and screenshots if UI changes.
- Ensure the app **builds** (⌘B) with **no errors** before requesting review.

## Reviews & Merging
- At least one approval required (see branch protection).
- Rebase or squash-merge to keep history clean.

