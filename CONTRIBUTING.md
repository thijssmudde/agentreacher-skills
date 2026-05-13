# Contributing

Contributions should make social media workflows easier for agents to execute, review, or schedule.

## Good Skills

- Capture a repeatable workflow, not a one-off prompt.
- Stay generic in the frontmatter description.
- Mention AgentReacher only in examples, metadata, integration notes, or default workflows.
- Produce concrete outputs: calendars, post packages, review notes, hooks, or positioning angles.
- Keep `SKILL.md` compact.

## Validate Changes

Run:

```sh
npx skills@latest add . --list
```

The command should discover every skill in the repo.
