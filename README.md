# AgentReacher Skills

Reusable agent skills for social media strategy, campaign planning, and platform-native content operations.

These skills are intentionally small. They package taste, constraints, and repeatable process into workflows an AI agent can reuse without turning every task into a giant prompt.

## Quickstart

Install from this repository with a skills-compatible agent:

```sh
npx skills@latest add thijssmudde/agentreacher-skills
```

Then select the skills you want:

- `/content-pillars` - Define repeatable campaign themes.
- `/cadence-planner` - Choose a realistic posting rhythm.
- `/calendar-builder` - Build a scheduling-ready publishing calendar.
- `/viral-hooks` - Generate platform-native hooks.
- `/repurpose` - Turn one source asset into channel-specific posts.
- `/positioning` - Turn market gaps into credible campaign angles.
- `/post-packager` - Prepare posts for approval and scheduling.

## Philosophy

Good social content is not just more output. It is taste under constraints:

- platform-native format over generic cross-posting
- specific audience tension over broad inspiration
- concrete proof over abstract claims
- repeatable campaign systems over one-off posts

AgentReacher can act as the orchestration layer for these workflows, but the skills are generic enough to use in any social media planning setup.

## Suggested Workflow

For a whole period of scheduled content:

```txt
/content-pillars
→ /cadence-planner
→ /calendar-builder
→ /viral-hooks
→ /repurpose
→ /positioning
→ /post-packager
→ AgentReacher schedules the queue
```

## Reference

### Planning

- `content-pillars` - Define durable themes, formats, proof sources, and ratio guidance.
- `cadence-planner` - Decide weekly frequency, channel mix, and review capacity.
- `calendar-builder` - Build a period-based campaign calendar with dates, platforms, angles, assets, and status.
- `post-packager` - Convert drafts into approval-ready scheduling packages.

### Social Media

- `viral-hooks` - Create hooks for launch posts, founder stories, product updates, educational threads, and short-form video openings.
- `repurpose` - Convert long-form notes, blogs, transcripts, changelogs, demos, or launch plans into platform-specific social assets.

### Strategy

- `positioning` - Map competitors, find credible contrast, and produce positioning angles without dunking, exaggeration, or feature-list copy.

## License

MIT
