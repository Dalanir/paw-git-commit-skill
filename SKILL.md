---
name: "@dalanir/git-commit"
version: "1.0.0"
description: "Generates clear, conventional git commit messages based on staged diff"
category: "workflow"
tags: ["git", "commit", "conventional-commits"]
license: "MIT"
compatibility: "Requires git"
allowed-tools: Bash(git:*) Read
---

# Git Commit
Generates a conventional git commit message based on the staged changes.

# Instructions
1. Run `git diff --staged` to see what's staged
2. Analyze the changes — identify the type: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`
3. Write a commit message following the format: `type(scope): short description`
4. Keep the subject line under 72 characters
5. If the change is complex, add a body explaining the *why*
6. Run `git commit -m "<message>"` with the generated message

#Examples
- `feat(auth): add GitHub OAuth login`
- `fix(parser): handle empty frontmatter gracefully`
- `docs(readme): update install instructions`

