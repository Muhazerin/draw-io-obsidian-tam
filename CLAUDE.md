# Git Workflow

Never push changes directly to main. Always create a new branch before committing.

Branch naming:
- `feat/<short-desc>` for new features
- `fix/<short-desc>` for bug fixes
- `refactor/<short-desc>` for refactors

The description is max 3 words, kebab-cased. Push to the branch, then merge via PR.

Before creating a branch, always check `git diff --stat` and `git status` to see ALL pending changes. Think about the overall theme, then create one branch that covers all related changes.
