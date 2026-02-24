# my claude setup

Full-stack dev with superpowers, claude-hud, and context7

> by pjs7678

`typescript` `superpowers` `claude-hud` `context7`

## Install

```bash
claude-dotfiles install pjs7678/claude-dotfiles
```

## What's Included

### Plugins

- **code-simplifier** (claude-plugins-official) v1.0.0
- **claude-hud** (claude-hud) v0.0.6
- **context7** (claude-plugins-official) v99e11d959269
- **superpowers** (claude-plugins-official) v4.3.1
- **ralph-loop** (claude-plugins-official) v99e11d959269
- **clangd-lsp** (claude-plugins-official) v1.0.0

### Custom Skills

- codebase-visualizer

### Plugin Skills

#### superpowers (claude-plugins-official v4.3.1)

- **using-git-worktrees** — Use when starting feature work that needs isolation from current workspace or before executing implementation plans - creates isolated git worktrees with smart directory selection and safety verification
- **test-driven-development** — Use when implementing any feature or bugfix, before writing implementation code
- **systematic-debugging** — Use when encountering any bug, test failure, or unexpected behavior, before proposing fixes
- **using-superpowers** — Use when starting any conversation - establishes how to find and use skills, requiring Skill tool invocation before ANY response including clarifying questions
- **dispatching-parallel-agents** — Use when facing 2+ independent tasks that can be worked on without shared state or sequential dependencies
- **executing-plans** — Use when you have a written implementation plan to execute in a separate session with review checkpoints
- **finishing-a-development-branch** — Use when implementation is complete, all tests pass, and you need to decide how to integrate the work - guides completion of development work by presenting structured options for merge, PR, or cleanup
- **brainstorming** — You MUST use this before any creative work - creating features, building components, adding functionality, or modifying behavior. Explores user intent, requirements and design before implementation.
- **writing-plans** — Use when you have a spec or requirements for a multi-step task, before touching code
- **requesting-code-review** — Use when completing tasks, implementing major features, or before merging to verify work meets requirements
- **receiving-code-review** — Use when receiving code review feedback, before implementing suggestions, especially if feedback seems unclear or technically questionable - requires technical rigor and verification, not performative agreement or blind implementation
- **writing-skills** — Use when creating new skills, editing existing skills, or verifying skills work before deployment
- **verification-before-completion** — Use when about to claim work is complete, fixed, or passing, before committing or creating PRs - requires running verification commands and confirming output before making any success claims; evidence before assertions always
- **subagent-driven-development** — Use when executing implementation plans with independent tasks in the current session

### Settings

Custom Claude Code settings included (sensitive data stripped).

### Permissions

Pre-configured permission rules for common tools.

---

*Generated with [claude-dotfiles](https://github.com/claude-dotfiles/claude-dotfiles)*